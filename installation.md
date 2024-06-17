# Installing Django
## Throughout this whole journey I will be using Linux syntax for all command line processes.

- Django is installed using the Python package manager ```pip```
___
- Firstly check the installed Python version using ```$ python3 --version```
- Then we create the virtual environment
  - ```$ mkdir hello_django```
  - ```$ cd hello_django```
- To open the current folder in vs code use ```$ code .```
- To create a virtual environment or venv as I will refer to it from now on, use ```$ python3 -m venv venv``` ```$ source ./venv/bin/activate```
___
- Next we'll create a package mangement file
- From within the hello_django directory ```$ touch requirements.txt```
- Then ```$ Django > requirements.txt```
- To install Django and any packages we may use along with it ```$ pip install -r requirements.txt```
___
  
