# Flask Blog

This is a Flask-based blogging application. Users can register, log in, and comment on posts. Admin privileges are available to manage posts: add, edit and delete them.

## Installation

* Clone the repository to your local machine.
* Ensure that Python 3.x is installed.
* Open a terminal window and navigate to the project directory.
* Install the required packages by running:

```pip install -r requirements.txt```

Set up environment variables:
`FLASK_KEY`: Secret key for Flask.
`DB_URI`: URI for the database (optional, defaults to SQLite).

## Usage
1. Run the application by executing python app.py in the terminal.
2. Access the application via a web browser at http://localhost:5000.
3. Register an account to create, edit, and delete blog posts.
4. Log in with your credentials to access your account.
5. Browse existing posts, view details, and leave comments.

## File Structure
* `main.py`: Main application file containing Flask routes and configurations.
* `forms.py`: Contains form classes for user registration, login, post creation, and comment submission.
* `templates/`: Directory containing HTML templates for rendering pages.
* `static/`: Directory for storing static files like CSS stylesheets and images.
* `requirements.txt`: File listing all required Python packages for installation.

## Dependencies
* Flask: Web framework for building the application.
* Flask-Bootstrap5: Integration of Bootstrap5 for styling.
* Flask-SQLAlchemy: Flask extension for working with SQLAlchemy, an ORM for database management.
* Flask-CKEditor: Extension for integrating CKEditor for rich text editing.
* Flask-Login: Extension for managing user sessions and authentication.
* Flask-Gravatar: Extension for generating Gravatar URLs for user profile images.
* SQLAlchemy: SQL toolkit and ORM for Python.

## Credits
* Original idea and app structure by Angela Yu, 100 Days of Code - The Complete Python Pro Bootcamp
* Bootstrap Theme: Start Bootstrap - Clean Blog
 - Copyright 2013-2023 Start Bootstrap
 - Licensed under MIT (License)