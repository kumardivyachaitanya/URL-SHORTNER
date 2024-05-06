# URL Shortener
A simple URL shortener built using Flask and SQLAlchemy. This application generates a unique short URL for any given long URL.

## Prerequisites
1. Python 3.x

2. Flask

3. SQLAlchemy

## Installation
1. Clone the repository

    `git clone https://github.com/arunimabarik75/URL-Shortener.git`

2. Navigate to the project directory

    `cd URL-Shortener`

3. Create a virtual environment

    `python -m venv venv`

    `venv\Scripts\activate`

4. Install all the required packages

    `pip install -r requirements.txt`

5. Run the `app.py` file to start the application

    `python app.py`

    The server will run on http://localhost:5000 in your browser

## Usage
1. Enter a long URL in the input field and click on "Generate Short URL".

2. The application will generate a unique short URL, which can be used to access the long URL.

3. The short URL is a 6-character alphanumeric string, generated using the random library of Python.

4. The new URL can be copied to clipboard for future use.

5. The `/all_urls` route displays all the long and corresponding short URLs present in the database.

## Technology Stack
1. Flask: A lightweight web framework for building APIs in Python.

2. SQLAlchemy: A SQL toolkit and Object-Relational Mapping (ORM) system for Python, which provides a full suite of well known enterprise-level persistence patterns.

3. HTML, CSS, Bootstrap: Used for the frontend of the application.

## Database
The database used is SQLAlchemy. The Urls class in the code represents the table in the database, which contains two columns: long and short. The long column stores the long URL, and the short column stores the corresponding short URL.

