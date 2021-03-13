# Coffee Shop Full Stack

## Full Stack Nano - IAM Final Project

Udacity has decided to open a new digitally enabled cafe for students to order drinks, socialize, and study hard. But they needed help setting up their menu experience.

This application displayes makes certain endpoints available to certain users. 
For example, baristas will be able to
    -- See the recipe information.
 Managers will be able to:
    --  create new drinks and edit existing drinks.


#### Virtual Enviornment

It is recommend working within a virtual environment whenever using Python for projects. This keeps your dependencies for each project separate and organaized. Instructions for setting up a virual enviornment for your platform can be found in the [python docs](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)

#### PIP Dependencies

Once you have your virtual environment setup and running, install dependencies by naviging to the `/backend` directory and running:

```bash
pip install -r requirements.txt
```

All backend code follows PEP8 style guidelines['https://www.python.org/dev/peps/pep-0008/']

### Backend

The `./backend` directory contains a completed Flask server with a pre-written SQLAlchemy module to simplify your data needs. I to completed the required endpoints, configured, and integrated with Auth0 for authentication.

## Running the server

From within the `./src` directory first ensure you are working using your created virtual environment.

Each time you open a new terminal session, run:

```bash
export FLASK_APP=api.py;
```

### Frontend

The `./frontend` directory contains a complete Ionic frontend to consume the data from the Flask server.

## Running Your Frontend in Dev Mode
To run the development server, cd into the `frontend` directory and run:

```bash
ionic serve
```
