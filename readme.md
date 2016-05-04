user authentication app in django/python containing code from book: Django By Example

to get this running:  
1. python manage.py createsuperuser  
2. python manage.py makemigrations  
3. python manage.py migrate  
visit http://localhost:8000/account/  
or http://localhost:8000/admin/  

To start the app I did the following:  
django-admin startproject kgauthapp1  
cd kgauthapp1  
django-admin startapp account  
then some code copies and refactors to bring this in line with latest django releases(such as sorting "Support for string view arguments to url() is deprecated" messages)  
