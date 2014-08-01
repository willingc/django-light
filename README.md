This is a lightweight Django template based on the book, "Lightweight Django"
by Julia Elman and Mark Lavin.

Project Template
----------------
To create a new project based on the current simple project template:

    $django-admin.py startproject foo --template=project_name

To run the application:

    $python foo.py runserver


Misc
----
To start gunicorn:
    gunicorn hello --log-file=_

To start simple runserver:
    python hello.py runserver
