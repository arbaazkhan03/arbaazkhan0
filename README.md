This multiple user behaviour will be easily extensible to future projects.
My MVT framework is Django with HTML,CSS,Bootstrap and JavaScript  on the frontend.
 Files Includes With This Project:
 In static folder:-Css and JS files
 In templatge folder:- All HTML files
Base.html                        About.html
Post form.html                   Post draft.html
Post confirm delete.html         

>>Setting of Django
For installation of Django:-
a) intall python or anaconda
b)install django using pip or do it from conda, go to  conda site
c) or use anaconda prompt to do all the steps, only if in above appliction django is not working well.

>>We use models to incorporate a database  into Django project.
-----Set up of Models---- 
1. Make classes and stirng represtion of each class
using __str__.return what you want

2. migration apply

3. use python manage.py makemigrations appname

4.then again manage.py migration use

5.use shell command to test
a)pythoon manage.py shell
use it

6.Since Shell is not good method so we use admin.py file
is a good method 
a) from appname.models import model names eg. topic,accessname
b) admin.site.register(modelname)

7. python manage.py Superuser
it will allow you to make email and pass etc.

8. for use of  admin who is going into backend 
use /admin following url
in order to fully use of admin and database,we will need superuser.

