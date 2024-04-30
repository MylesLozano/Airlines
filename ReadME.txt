(pip installation process for database integration in Django)
Make sure to remove <> and insert your own unique name.

pip install django - installs django
.\venv\Scripts\activate - activate virtual environment (.env)
pip install psycopg2-binary - used to integrate postgres to Django
pip install python-dotenv - used to hash crucial credentials

django-admin startproject <projectname> . - creates new project
python manage.py runserver - run Django server
python manage.py startapp <appname> - new application
python manage.py makemigrations - update the tables in the database
python manage.py migrate - migrate data in the database
python manage.py createsuperuser - creates an admin page
