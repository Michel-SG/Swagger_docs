# Swagerdocumentation

``
Tested with Python 3.11.4
Dependencies listed in file `requirements.txt`.
To get swagger docs example, just enter 'swagger editor' term to your browser
``

## Projet setup

### Move into Swagerdocumentation folder and create a virtual environment by using cli:
``
    on windows: py -3 -m venv venv
    on macOs/Linux: python3 -m venv venv
``
### Activate the virtual environment by using cli:
``
    on windows: venv\Scripts\activate
    on macOs/Linux: . venv/bin/activate
``
### Move into Swagerdocumentation folder and install the requirements packages by using pip package:
``
    pip install -r requirements.txt
``
## To enable all development features, set the FLASK_ENV environment variable to development
### Make sure to use the following command from the Swagerdocumentation folder:
``
    export FLASK_APP=swagger_docs.app
``
## Compiles and host-reloads for development
### Move into swagger_docs folder and use the following command to run the application:
``
    flask run
``