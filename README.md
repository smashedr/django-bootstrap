# Django Bootstrap

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/497db940dd304934abc4e7f554f261f5)](https://www.codacy.com/app/smashedr/django-bootstrap?utm_source=github.com&utm_medium=referral&utm_content=smashedr/django-bootstrap&utm_campaign=badger)
[![Build Status](https://travis-ci.org/smashedr/django-bootstrap.svg?branch=master)](https://travis-ci.org/smashedr/django-bootstrap)
[![Coverage Status](https://coveralls.io/repos/github/smashedr/django-bootstrap/badge.svg?branch=master)](https://coveralls.io/github/smashedr/django-bootstrap?branch=master)

A Django Bootstrap Template Including:

### User Interface

Static files include:

- Bootstrap (3.3.7)
    - http://getbootstrap.com/
- JQuery (3.1.1)
    - https://jquery.com/
- Font Awesome (4.7)
    - http://fontawesome.io/

### Django

Default setup uses these modules:

- Logging
    - https://docs.python.org/3/library/logging.html
    - https://docs.djangoproject.com/en/1.10/topics/logging
- ConfigParser
    - https://docs.python.org/3/library/configparser.html

### Python 2

Notes for running under Python 2:

- Add `configparser` to the `requirements.txt`.
    - Or run `pip install configparser` manually.
- Use `virtualenv` instead of `venv`.

## Copying This Project

To clone a clean copy of this project int your repository:

1. `cd` into development directory
2. `git clone https://git.cssnr.com/shane/django_bootstrap.git .`
3. `rm -rf .git`
4. `git init`
5. `git remote add origin https://github.com/your-name/your-repo.git`
6. `git push -u origin master`

## Deployment

To deploy this project on the development server:

1. `cd` into deploy directory
2. `git clone https://git.cssnr.com/shane/django_bootstrap.git .`
3. `pyvenv venv`
4. `source venv/bin/activate`
5. `pip install -r requirements.txt`
6. `cp settings.ini.example settings.ini`
7. Edit the settings to your preference.
8. `python manage.py runserver 0.0.0.0:8000`
