# Blog Website
This was my DBMS project in Semester 5
A blogging website built mainly using the Python - DJANGO framework.
Any user can make an account and write posts. Other users can comment on the posts. Comments are visible to the public only if the author has approved them. Other features include editing and deleting posts. Also posts can be temporarily saved as Drafts and published later.
For security purposes, ARGON 2 Password Hashing algorithm has been used for authentication of users. Uses SQLite for the backend database.
Technologies Used - Front End - HTML, CSS, Bootstrap
Back End - Django, SQLite

##### Deployed at - [https://ayushjain.pythonanywhere.com/](https://ayushjain.pythonanywhere.com/ "https://ayushjain.pythonanywhere.com/")

### Steps for Setting up locally

------------

#### Create a virtual environment
    python3 -m venv blog_proj
#### Activate virtual environment
    source blog_proj/bin/activate
#### Install the required packages
    pip3 install django==2.2.5
    pip3 install bcrypt
    pip3 install argon2_cffi==16.3.0
#### Initialize the database
    python3 manage.py makemigrations
    python3 manage.py migrate
#### Create an admin user
    python3 manage.py createsuperuser
#### Run locally
    python3 manage.py makemigrations
    python3 manage.py migrate
    python3 manage.py runserver

##### The site would be served locally at &nbsp; [http://127.0.0.1:8000/](http://127.0.0.1:8000/ "http://127.0.0.1:8000/")

##### Django Admin page - [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin "http://127.0.0.1:8000/admin")


