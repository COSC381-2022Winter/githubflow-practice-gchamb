# Movies Website for COSC 381
## Steps for starting website in development

Steps:
1. Create a virtual environment in the root directory:  `python3 -m venv venv`

2. Activate the virtual environment: `source venv/bin/activate`
3. Install the dependencies: `python3 -m pip install -r requirements.txt`
4. Set up environment variables for the flask app: `source env-var.sh`
5. Initialize the database: `flask init-db` after the database is intialized, the database file is at: `instance/flaskr.sqlite`
6. Start the website: `flask run`
7. The webpage can be checked with this URL: http://127.0.0.1:5000/movies/
8. To stop the app: `crtl + c`
9. To stop the virtual environment: `deactivate`