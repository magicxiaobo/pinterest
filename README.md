
This is the pinteresting application for 
[*One Month Rails*] (http://onemonthrails.com)

The address is http://brian-pinterest.herokuapp.com


Brian Z



1. Configuration of developing environment
   My ruby version: ruby 1.9.3p547	
   My rails version: rails 4.1.1
   In terminal, using “$ruby -v”  and “$rails -v” to check the version of ruby and      rails installed.

   Editor, I recommend “sublime”.

2. $pwd: to check the directory you are in
   $ls: stands for the list
   $cd + “folder”: open the folder

3. Debugging: Googling.
   You usually can get answer from Stackflow

4. Commit with github
   
   Config a Git on a new computer
	$git config –-global user.name “Brian Z” 
   	$git config –-global user.name
   	$git config --global user.email "yuxiaobohit@gmail.com"
   	$git config --global user.email

   Setting up Git in a new project
	$git init
	$git status
	$git add .
	$git commit -am “init commit”

   Edit your .gitignore file
	Add .DS_Store to your /.gitignore file so that git doesn't keep track of this random file.(only)

   Git it back if you deleted something in your code you shouldn't have
	$git add .
	$git checkout -f

5. Push changes from your computer to GitHub
	$git add .
	$git commit -am “	Message”
	$git push

6. Creating Your Homepage
	(1).Are you in the Pinteresting directory? (where to store your web app directory)
	$cd ~/Desktop
	$cd pinteresting
	$rails server
	(2).Create a new page
	$rails generate controller pages home
	In your browser, go to the URL: localhost:3000/pages/home and see the new blank homepage you just created
	
7. Creating more pages
	Most likely, you're going to need more pages.You'll have to add a new view and set a route for it.
	(1). Add a new action in your controller
		def about
		end
	(2). Update the HTML in your view

8. Embedded Ruby
	(1).Change your HTML link to an embedded ruby link
	<%= link_to “here”, “#” %>
	(2).Review of the lesson
	In html, a link looks like this
		<a href=”#”>here</a>
	In Ruby on Rails a link will look like this
		<%= link_to “here”, “#” %>

9. Create Navigation links
	<%= link_to “Home”, root_path %>
	<%= link_to “About”, about_path %>	

10. Installing the Bootstrap Gem
	(1). Add the Bootstrap gem
	In Gemfile, 
		..
		gem 'bootstrap-sass'
		..
	(2). bundle install to install a gem
		$bundle install
	(3). Understand the Application.css file
	Application.css takes all the other files in your /stylesheets directory and combines them for you run your app.
	(4). Create a new scss file
		@import 'bootstrap';
	(5). Restart server
		Ctrl + C
		$rails server

11.

