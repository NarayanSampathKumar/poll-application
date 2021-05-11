# poll-application

First create a virtual environment and activate it,

If virtual environment is not installed follow:

1. python3 -m pip install --upgrade pip
2. python3 -m pip install virtualenv
3. python3 -m venv env
4. On macOS and Linux: 
     source env/bin/activate
   On Windows:
     .\env\Scripts\activate

To Run this application 

1. First import all the packages in the requirements.txt using the command "pip install -f requirements.txt"
2. Once Pip installs the required modules run "python manage.py migrate"
3. Then start the application using command "python manage.py runserver 0.0.0.0:8000"
4. The application runs on default port 8000, access the below url to access the application

http://localhost:8000/


Running on Docker:
to run this app on docker 
1. cd to the application directory where docker-compose file is present
2. Run command "docker-compose build"
3. And run "docker-compose up"
4. Once done the application will be served at "http://127.0.0.1:8000/"
5. And should look like below

![image](https://user-images.githubusercontent.com/82889747/117762876-8ba1f000-b247-11eb-8172-4838e5943dc1.png)

 
