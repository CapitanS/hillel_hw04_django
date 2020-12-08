--------------------
Homework_04. Django unchained.
--------------------
--------------------
>The goal of this project to learn how to install django and start new project, create new application 
> and *DO NOT* show secret key in my repo.

P.S. Among other things to consolidate skills with the creation of virtual environment, 
creating a .gitignore, creating requirement.txt etc.
---------------------
### Tasks:
1. Create new repo.
2. Use `git clone`.
3. Create virtual environment.
4. Create `.gitignore`.
5. Add to `.gitignore` venv, database, .idea.
6. Create `requirement.txt`.
6. Initiate new django project `django_example`.
7. Create new application `catalog`.
8. Add this app to `INSTALLED_APPS`.
9. Check that `SECRET_KEY` takes from the environment values.
10. Describe the project in `README.md`.
11. `git commit`, `git push`, `pull request`, `merge`.
---------------------
### Cheatsheet for this project:
1. Create new project.
```sh
$ django-admin startproject django_example .
```
2. Create new application.
```sh
$ python manage.py startapp catalog
```
### License

ISC