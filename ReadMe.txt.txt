This is an international conference management system , where users from all around the world can meet virtually

The languages used for building the application:
Python
Django
HTML
CSS
javaScript

Steps to run the code:
1. Download and extract all the files and folders from the zip file 
2. cd into the required directory and run the below code to install all the requirements 
        pip install -r requirements.txt
3. Create an Agora account in agora.io , under which create a project .Copy the app id and app credentials , into the respective fields at views.py and stream.js
4. Start the live server from index.html in the ProjectHTML folder
5.Run the below code in the terminal to allow the application to use the video conference feature
	python manage.py runserver