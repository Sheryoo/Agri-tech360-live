# Agri-tech360

## Requirements

Python 3.8–3.11

## Installation

First, clone this repository.

    $ git clone https://github.com/Sheryoo/Agri-tech360.git
    $ cd Agri-tech360

Then, add your .env file with this data:

    $ HOST = .....
    $ PORT = ....
    $ SECRET_KEY = ....
    $ OPEN_WEATHER_API_KEY = ....
    $ PLANT_ID_API_KEY = ....
    $ PLANT_API_KEY = ....
    $ GEMINI_API_KEY = ....

Then, Create venv and activate it:

### For Windows:

    $ python -m venv env
    $ source env/bin/activate

### For Mac or Linux:

    $ python3 -m venv env
    $ source env/bin/activate

After, install all necessary to run:

### For Windows:

    $ pip install -r requirements.txt

### For Mac or Linux:

    $ pip3 install -r requirements.txt

Than, run the application:

### For Windows:

    $ python app.py

### For Mac or Linux:

    $ python3 app.py

To see your application, access this url in your browser:

    http://{HOST}:{PORT}
