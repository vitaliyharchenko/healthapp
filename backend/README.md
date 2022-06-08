# Folder structure

```
/conf - folder with settings and core urls
.gitignore - instruction for temporary files
db.sqlite3 - file with database
manage.py - python entry file
```

# Installation and virtual env

This project will use 4.0 version of Django ([Docs](https://docs.djangoproject.com/en/4.0/))

You must install python and pip packages in virtual environment. That can avoid issues with different versions of libraries. ([Article](https://help.dreamhost.com/hc/en-us/articles/215317948-How-to-install-Django-using-virtualenv))

```
python3 -m venv ~/Dev/venv // Create folder with local packages version
source venv/bin/activate // Activate virtual env
pip install Django // Install Django in virtual env
deactivate // quit from virtualenv
```

# Commands

```
python manage.py runserver (-d) - start django server (in daemon mode)
```

Django have included admin panel/ For using it you must create admin user named superuser. I prefer use "root@root.root - root" pair.

```
python manage.py createsuperuser
```

# TODO's

-   [ ] Create user model
-   [ ] Set up Django-rest-framevork for API
-   [ ] Learn how to authenticate through API
