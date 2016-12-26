# Django Bootstrap

[![build status](https://git.cssnr.com/shane/django_bootstrap/badges/master/build.svg)](https://git.cssnr.com/shane/django_bootstrap/commits/master) [![coverage report](https://git.cssnr.com/shane/django_bootstrap/badges/master/coverage.svg)](https://git.cssnr.com/shane/django_bootstrap/commits/master)

A Django Bootstrap Template Including:

### User Interface

Static files include:

- Bootstrap (3.3.7)
    - http://getbootstrap.com/
- JQuery (3.1.1)
    - https://jquery.com/
- JQuery UI (1.12.0)
    - https://jqueryui.com/

### Django

Default setup uses these modules:

- Logging
    - https://docs.python.org/3/library/logging.html
- ConfigParser
    - https://docs.python.org/3/library/configparser.html

### Python 2

Notes for running under Python 2:

- Add `configparser` to the `requirements.txt`.
    - Or run `pip install configparser` manually.
- Use `virtualenv` instead of `venv`.

## Deployment

1. `cd` into deploy directory
2. `git clone https://git.cssnr.com/shane/django_bootstrap.git .`
3. `pyvenv venv`
4. `source venv/bin/activate`
5. `pip install -r requirements.txt`
6. `cp settings.ini.example settings.ini`
7. Edit the settings to your preference.
8. `python manage.py runserver 0.0.0.0:8000`
