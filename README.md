# djangoPolls
[![Build Status](https://travis-ci.org/trjahnke/djangoPolls.svg?branch=master)](https://travis-ci.org/trjahnke/djangoPolls) [![codecov](https://codecov.io/gh/trjahnke/djangoPolls/branch/master/graph/badge.svg)](https://codecov.io/gh/trjahnke/djangoPolls)\
Django Project polls web application

# How to use
Find a directory you would like to work in and clone the repo (https://github.com/trjahnke/djangoPolls.git). Now let's create a virtual environment. I use virtualenv but it really doesn't matter as long as you use Python 3 you'll be fine. For virtualenv `cd` into the repo directory and run the following command to generate a basic Python 3 env (you can install virtual with: `pip install virtualenv`):
```
virtualenv -p python3 env
```
This will make a Python 3 environment named env.

Now start the environment with:
```
source env/bin/activate
```
Once it is activated install the required packages:
```
cd mysite
python install -r requirements.txt
```
Make sure to run the Django server
```
python manange.py runserver
```


## ToDo - not in any order
- Landing page
    * Make one
    * Set it up to override django sign on and sign up 
- Setup user login and creation 
    * at some point set this up to do third party login
- fancy up the admin console
- page redesigns
- add additional testing for better coverage




