# User login and register system implementation in django
&nbsp;


## Prerequisites

- Python 3
- pip 3

## Virtualenv & Dependencies

create a virtualenv and run requirements.txt<br/>
<b>virtualenv</b>

<pre>python -m pip install virtualenv</pre>

Following command will create virtual environment directory named venv in your projects.
<pre>python -m virtualenv venv</pre>

Following command will activate the virtual environment for your project. 
<pre>.\venv\Scripts\activate</pre>

After this steps, `(venv)` should be appier at the begning of terninal line, like below which 
confirms virtual environment is successfully activated.

to run requirements.txt

<pre>$ python -m pip install -r requirements.txt</pre>

here <b>venv/</b> folder contains all dependencies

## Running locally

<ol>
  <li>
      clone repository or download the code from GitHub
      <pre>$ git clone </pre>
  </li>   
  <li>
    run migrations
    <pre>$ python manage.py migrate</pre>
  </li>
  <li>
    now, runserver
    <pre>$ python manage.py runserver</pre>
  </li>
 </ol>


### Implement Token Authentication using Django REST Framework

Token authentication refers to exchanging username and password for a token that will be used in all subsequent requests so to identify the user on the server side.This article revolves about implementing token authentication using Django REST Framework to make an API. The token authentication works by providing token in exchange for exchanging usernames and passwords.

---
<b>install django rest_framework</b>
<pre>$ pip install djangorestframework</pre>
---

## error when trying to migrate or attempting to runserver

Simply try "python3 manage.py migrate" or "python3 manage.py runserver" instead

or

Django is not installed (or installed properly)