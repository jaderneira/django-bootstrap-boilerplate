

# Django project with Bootstrap and font-awesome
<img src="https://img.shields.io/badge/django-3.1.5-green"><img src="https://img.shields.io/badge/bootstrap-5.0.0--beta1-purple"><img src="https://img.shields.io/badge/fontawesome-5.15.2-navy"><img src="https://img.shields.io/static/v1?label=licence&message=GPL&color=blue"><img src="https://img.shields.io/static/v1?label=build&message=passing&color=green">

## Usage

Create a project directory and install a python virtual environment inside it

```bash
mkdir project && cd project
python3 -m venv venv
source venv/bin/activate
```

Create a source dir and clone the repository

```bash
mkdir src && cd src
git clone https://github.com/jaderneira/django-bootstrap-boilerplate .
```

Install the dependencies

```bash
pip install -r requirements.txt
```

Run the migrations and start the server!

```bash
python manage.py migrate
python manage.py runserver
```

Yay! App running in `http://127.0.0.1:8000` :)