# To-Do List Application

My first Django project, which aims to help to user to keep track on his tasks using a simple graphical user interface (GUI) for interaction with the app.

## Project Hierarchy

The project consists of the following files and folders:

- 'db.sqlite3': Enables the connection to the sqlite database.
- 'manage.py': automatically created in each Django project, it enables command-line utility for administrative tasks.

### Folders
1. 'todo': Contains our app settings and list of urls.
   - 'settins.py':
   
2. 'tasks': Contains the both the frontend and the backend logic.
   - 'views.py': Contains functions that takes HTTP request and returns HTTP response.
   -  'urls.py': Basically maps urls to their correct views function. (request -> responce)
   -  'models.py': Define the database of our web applications allowing us to Declare tables and fields of our database.
   -  'forms.py': Contains all of the forms code to keep our code easily maintainable.

## Getting Started

To run the BMC Via Simulation project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/BMC-Via-Simulation.git`
2. Install the required dependencies using pip: `pip install -r requirements.txt`
3. Open `MainWindow.py` and run it to start the GUI.


