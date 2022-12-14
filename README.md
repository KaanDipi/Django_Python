# ISD_realproject
This is the code for our Website 'Neighborhood Bulletin' as part of the ISD 2020 class

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. This website is for development purposes only, deployment is not intended.

### Prerequisites

Please follow these instructions:

First of all, a virtual environment has to be established
Setup using command prompt

* 1-make sure you are in related path in command prompt
* 2-install a virtual environment

```
pip install virtualenv
```
3-activate virtual environment
Linux & Mac:
```
source venv/bin/activate
```
Windows: 
```
venv\Scripts\activate
```
-> The virtual environment is working, when the name of it appears before the <base> tag in the terminal
### Installing

Execute the following order to install Django

```
pip install -r requirements.txt
```

First of all, migrations need to be done (make sure to be in the root directory, which is the one containing the manage.py file)

```
python manage.py makemigrations
```

```
python manage.py migrate
```

To start the server, execute 

```
python manage.py runserver
```
To be able to use the admin panel, create a superuser

```
python manage.py createsuperuser
```

## Deployment

No deployment planned

## Built With

* [Django](https://docs.djangoproject.com/en/3.0/) 
* [Bootstrap](https://getbootstrap.com/) 
* [Font Awesome](https://fontawesome.com/6?next=%2F) 


