#Please read this file!

this file will store all the commands for this project._env

##Python

python -m venv env  <--- Creates a virtual env
env\Scripts\activate

Microsoft SQL Server Management Studio
(LocalDb)\MSSQLLocalDB

pip install django
pip install mssql-django
django-admin startproject blog

django-admin startproject blog
cd blog
python manage.py startapp article
python manage.py runserver

DATABASES = {
    'default': {
        'ENGINE': 'mssql',
        'NAME': 'Blog',
        'HOST': '(LocalDb)\MSSQLLocalDB',
        'PORT': '',
        'USER':'',
        'PASSWORD': '',
        'OPTIONS':{
            'DRIVER': 'ODBC Driver 17 for SQL Server',
        }
    }
}

Microsoft SQL Server Management Studio
Right Click Database -> New Database
Key in Blog -> ok

python manage.py runserver

python manage.py makemigrations
python manage.py migrate

python manage.py createsuperuser
admin
admin@root.com
1234
1234
