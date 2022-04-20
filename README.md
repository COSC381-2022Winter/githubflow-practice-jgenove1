# Welcome to the COSC 381 movies website!
## Getting started

* clone or download the repository into a location of your choice

* set up a virtual environment by running:

        python3 -m venv venv

* activate the virtual environment by running:

        source venv/bin/activate

* install the project requirements by running:

        pip3 install -r requirements.txt

* set up the environment variables for Flaskr:

        source env-var.sh

* initialize the database:

        flask init-db

* start the server:

        flask run

* you will see out put similar to the following:

        Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

* navigate to `http://127.0.0.1:5000/movies` to check that the website is running