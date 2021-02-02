# my-wag-site
https://docs.wagtail.io/en/stable/getting_started/tutorial.html

## Commands

To update the database with your model changes. You must run the below commands each time you make changes to the model definition.
```
python manage.py makemigrations
python magange.py migrate
```

## Creating a new app
```
python manage.py startapp <newapp>
```
Add the new `<newapp>` app to INSTALLED_APPS in mysite/settings/base.py.

## Stopped on images on 2 Feb 2021