# Flask Project Layout

Flask Project layout is a beginner friendly starter template or project layout adapted from flask template layout proposal [check the link here ](https://flask.palletsprojects.com/en/2.0.x/tutorial/layout/).

Ever wondered how to structure your flask project? Well, flask-project-layout template just does that for you. It comes with an empty '.py' files and '.html' with relevant or commonly used python/flask file names. The main goal of this project is to show the beginners/ or anyone who is new to flask the best practices on structuring your code and project files.
 
You are required to rename the files to your liking based on your project goal. For example if you are building a flask application for online event, It's fair enough to rename the blog folder to something that relates to your project. 

Once you have this installed, you can expand the layout depending on how big your project is. 

## Description
The project directory contain the following:

    project_name/ - This is your python project package; it contains all your project code and files. Inside this directory you will find folders and files. Let's start with .py files. 
            . __init__.py : There are so many explanations of usage of this dunder method, but for simplicity, this method turns a directory into a python module. 
                    it's   lets a python interpreter know that a directory contains a code for python module.

            . auth.py : For writing user authentication logic. 

            . blog.py: Anything related to updating, creating, deleting; Focus in operations/logic that mainly focus the blog part of your application.

            . db.py : for operations pertaining database such 


        static/ - Contain your site static files such as images, style.css, fonts, javascript etc.
        templates/ - Contain your site html content.

    setup.py - Will contain installation files that will tell python how to install your project. 

    tests/ - The test folder contain files that will be used to perform your program testing. 


## Rename directories and files
        Once you have installed this project in your working directory, it's recommended that you rename some file and directories to something descriptive.
        For example; you can rename 'project_name' folder to 'flask_sporty', 'online_banking_project', 'my_portfolio', etc.
        
        You can rename static and templates folder as well, however, flask doesn't recommend developers to change it. It's a conventio !!!!  


## How to install
        Terminal windows :
                mkdir 'parent_directory'
                cd parent_directory

                git clone https://github.com/gilbertekalea/flask-project-layout.git

                and there you go ... 

                Happy hacking bud !! 










