# Welcome to the COSC 381 movies website!
## Getting started with local development

Warning: do not use these instructions to deploty to production!

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

<hr>

## Making the site externally accessible (for testing when developing on a remote machine)

* after the server is started, in the terminal window of VSCode, there will be a tab labelled `PORTS`

* click this tab and check that the remote port has been forwarded to the local machine

* if the port has not been automatically forwarded, you will have to maunally forward it by clicking the `add port` button

* enter the port to forward, and VSCode will forward that port to your local machine, so your local browser can access the webpage