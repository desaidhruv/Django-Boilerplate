<h1>Django Boilerplate</h1>
<p>This repository is a boilerplate Django project for quickly getting started.</p>

![django](https://user-images.githubusercontent.com/40533390/85207841-5b104980-b349-11ea-9004-76bbbcc68f2a.png)

<h2>Getting Started</h2>
Steps:
<ol>
<li>Clone/pull/download this repository</li>
<li>Create a virtualenv with <code>virtualenv env</code> and install dependencies</li>
<li>Configure your .env files.</li>
<li>Activate the virtual env using <code>Scripts/activate</code></li>
<li>You've setup the virtual env and you're good to run the project.</li>
</ol>
<h2>Installation</h2>
<pre>pip install django</pre>
<pre>pip install django-tinymce4-lite</pre>
<h2>Login</h2>
You can access the django admin page at http://127.0.0.1:8000/admin and login with username 'desaidhruv' and the password as 12345.
Also a new admin user can be created using
<pre>python manage.py createsuperuser</pre>
<h2>Usage</h2>
Go to mysite folder and run
<pre>python manage.py runserver</pre>
Then go to the browser and enter the url http://127.0.0.1:8000/

This project includes:
<ol>
<li>Register, Login and Logout forms are developed.</li>
<li>A model is created to display content on the Front-end.</li>
<li>Data of that model is displayed on the home page.</li>
</ol>
