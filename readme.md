Blog Project README
===================

This project is a simple blog application built using the Flask web framework and Bootstrap 5 for styling. The application allows users to view and interact with blog posts, including creating, editing, and deleting posts. Additionally, users can leave comments on blog posts.

Project Structure
-----------------

The project structure is organized as follows:

-   `app.py`: The main Flask application file containing the routes, models, and configurations.
-   `templates/`: This directory contains HTML templates used to render different pages of the application.
-   `static/`: This directory contains static assets such as CSS, images, and JavaScript files.
-   `models.py`: Defines the data models for the application using SQLAlchemy ORM.
-   `forms.py`: Defines forms used for data validation and input handling.
-   `config.py`: Contains configuration settings for the application.
-   `README.md`: This file contains information about the project and how to set it up.

How to Run the Application
--------------------------

1.  Install the required packages:

    bashCopy code

    `pip install Flask flask_sqlalchemy flask_login flask_wtf`

2.  Run the application:

    bashCopy code

    `flask run`

3.  Access the application in your web browser at `http://localhost:5000`.

Features
--------

-   User Authentication: Users can log in to the application using their credentials.
-   View Posts: Users can view all available blog posts on the homepage.
-   View Post Details: Users can click on a post to view its details, including title, subtitle, author, and comments.
-   Add/Edit/Delete Post: Admin users (user ID 1) can add, edit, and delete posts.
-   Leave Comments: Users can leave comments on blog posts.

Notable Code Sections
---------------------

-   `app.py`: Contains the main application routes, including routes for displaying posts, creating posts, editing posts, deleting posts, and leaving comments.
-   `models.py`: Defines the data models for the application, including `User` and `BlogPost` classes.
-   `forms.py`: Defines the forms for post creation and comment submission using Flask-WTF.
-   Templates: The `templates/` directory contains HTML templates for different application views, including the homepage, post details, and comment forms.
-   `render_form` Function: A custom template function to render form fields in the HTML templates.
-   `header.html` and `footer.html`: Reusable template snippets for the header and footer of the application.

Dependencies
------------

-   Flask: A micro web framework for Python.
-   Flask-SQLAlchemy: An extension that adds SQLAlchemy support to Flask.
-   Flask-Login: An extension that provides session management for user authentication.
-   Flask-WTF: An extension for handling web forms and validation.

Acknowledgments
---------------

This project was built as a learning exercise and is based on tutorials and documentation from the Flask and Bootstrap frameworks.