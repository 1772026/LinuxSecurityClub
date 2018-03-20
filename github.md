Install & Using Github in Ubuntu 16.04

    In this tutorial i will show you, how to using Github on Ubuntu 16.04 and create static blog or hosting your static HTML website in your Github Pages

Preparation

    Sign up your Github Account here
    Create a new repository named "username.github.io" (where username is your username on GitHub.)
    Search and download your HTML / Static Blog Themes

Installing Git on Ubuntu 16.04

$ apt-get install git

Create folder for local repository

$ mkdir blog && cd blog
$ cp /your/themes /to/your/local/folder

Setting your Git Username in Local Repository

$ git config --global user.name "Your Name"
$ git config --global user.email "Your Email"

Initialize and Access Remote Repository

$ git init
$ git add . 
$ git commit -m "your comment"
$ git remote add origin https://github.com/username/repository-name.git
$ git push -u origin master

Push Files to Github Repository

After you editing code or create new files, you can push your code to github repository with this command -> As a example i adding "CNAME" file that contain a site domain.

$ echo "hermawan.me" >> CNAME 	# optional
$ git add . 
$ git commit -m "Adding CNAME"
$ git push -u origin master
