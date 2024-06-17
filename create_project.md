# Creating a project
All of the following should be executed from within the hello_django folder that we created earlier.

- Run ```$ django-admin startproject helloproject . ```
- The period at the end tells django to use the current dir for the project. You can also specify the filepath if necessary.
___

- To run the project use ```$ python3 manage.py runserver```
- To create the Hello World app use ```$ python3 manage.py startappp hello_world```
- Find the settings.py file
- Inside the file, find the ```INSTALLED_APPS``` section
- Add the following to the end
```python
'hello_world.apps.HelloWorldConfig',
```
- The file should now contain code looking like the following
```python
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'hello_world.apps.HelloWorldConfig',
]
```

___
## Creating a view
- 
