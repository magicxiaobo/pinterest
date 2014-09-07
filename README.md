
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
	(1).
		

