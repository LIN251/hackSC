Ref: https://github.com/app-generator/react-flask-authentication

cd flask-api

python3 -m venv env

source env/bin/activate

pip install -r requirements.txt

export FLASK_APP=run.py

export FLASK_ENV=development

FLASK_APP=app.py FLASK_ENV=development flask run



cd react-ui

yarn

yarn start 