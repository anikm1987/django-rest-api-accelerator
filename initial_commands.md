Initial setup commands 
-----------------

After completeing pip install -r requirements.txt

- Create a project inside the folder - . is to avoid creating another folder
django-admin.py startproject accelerator_project .

- Create an app inside the project. Django project can have multiple project
python manage.py startapp api_app 

- Configure new app into the project
Navigate to /django-rest-api-accelerator/accelarator_project/settings.py and add your entries in INSTALLED_APPS section

- Running the development server and navigate to [http://localhost:8000](http://localhost:8000)
python manage.py runserver 0.0.0.0:8000

- You may get messages like below, dont worry about them as of now

You have 21 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, authtoken, contenttypes, sessions.    
Run 'python manage.py migrate' to apply them.

- Added our first endpoint inside api_app 
    - Check api_app/views.py, api_app/urls.py and accelarator_project/urls.py