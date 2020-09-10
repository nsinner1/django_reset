# Intro to Django

## Django REST framework

Lab: 28 - Django REST framework

*Author: Natalie Sinner and Harry Potter*

----

## Description
Rebuild a custom version of Blog API demo project from scratch.
Replace Blog and Post with your own application and model.
Your model must have at least as many fields as demo’s model.
Your model must have one field that is a foreign key to user.
NOTE: You are not required to build any templates for this lab.
Features - Docker
NOTE Refer to the class demo for built out Dockerfile and docker-compose.yml examples.
Update Dockerfile and docker-compose.yml if needed.

## Reference 
[StackOverFlow](https://stackoverflow.com/questions/40667519/why-is-django-throwing-error-disallowedhost-at)

---

### Getting Started
Clone this repository to your local machine.

```
$ git clone [https://github.com/nsinner1/django_rest]
```

### To run the program from VS Code:
Select ```File``` -> ```Open``` -> ```django-rest```

Next navigate to the location you cloned the Repository.

Double click on the ```django-rest``` directory.

Then select and open ```django-rest```

### To run in browser:
Locate directory in terminal

Activate virtual environment:

```
poetry init 
poetry shell
```
Once in virtual environment, run command:

```
python manage.py runserver
```

Once server is running, copy and paste URL: http://127.0.0.1:8000/

---

### Change Log
***[The change log will list any changes made to the code base. This includes any changes from TA/Instructor feedback]***  
1.3: *Set up Docker and new port* - 10 Sept 2020
1.2: *Set up server and verified links are correct between each page* - 9 Sept 2020  
1.1: *Set up scaffolding* - 9 Sept 2020  


------------------------------
For more information on Markdown: https://www.markdownguide.org/cheat-sheet