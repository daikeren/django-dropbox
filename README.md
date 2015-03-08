# django-dropbox-redux
> Version 0.0.5

# What

django-dropbox is a Django App that contains a Django Storage which uses Dropbox.

# Installing

## First of all

    pip install django-dropbox-redux

set DEFAULT_FILE_STORAGE in settings.py :

    DEFAULT_FILE_STORAGE = 'django_dropbox.storage.DropboxStorage'

additionally you must need to set the next settings:

    DROPBOX_ACCESS_TOKEN = 'xxx'

You will need to create an Dropbox app at [Dropbox for Developers](https://www.dropbox.com/developers). And then generated access token for your app. Then set `DROPBOX_ACCESS_TOKEN` settings in `settings.py`.
