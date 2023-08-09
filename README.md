# To-Do List Application

My first Django project, which aims to help to user to keep track on his tasks using a simple graphical user interface (GUI) for interaction with the app.

## Project Hierarchy

The project consists of the following files and folders:

- 'db.sqlite3': Enables the connection to the sqlite database.
- 'manage.py': automatically created in each Django project, it enables command-line utility for administrative tasks.

### Folders
1. 'todo': Contains our app settings and list of urls.
   - 'settins.py': Used to store configuration information in Django
   - 'asgi.py': Provide a standard interface between async-capable Python web servers, frameworks, and applications.
   - 'wsgi.py: Application callable which the application server uses to communicate with your code.
   
2. 'tasks': Contains the both the frontend and the backend logic.
   - 'views.py': Contains functions that takes HTTP request and returns HTTP response.
   -  'urls.py': Basically maps urls to their correct views function. (request -> responce)
   -  'models.py': Define the database of our web applications allowing us to Declare tables and fields of our database.
   -  'forms.py': Contains all of the forms code to keep our code easily maintainable.

## Getting Started

To run the To-Do List web application, follow these steps:

1. Clone the repository: `git clone https://github.com/MichaelBenIsrael/Todo_List_App_Django.git`.
2. Install the required dependencies using pip: `pip install -r requirements.txt`.
3. Open the terminal and change directory into the project's path using cd: 'cd <project path>'.
4. Run the sever using the command: 'python manage.py runserver'
5. Paste the returned url into your web browser and you are good to go!
