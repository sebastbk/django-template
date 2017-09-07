# django-template 1.0

Modified django project template based on the django 1.11 template.

Includes the following alterations:

* Main project application renamed to config to better match its typical usage.
* Includes a settings folder in config with the base settings base.py and four addtional files for different environments, local.py, testing.py, staging.py, and production.py. By default the local.py file will be used in manage.py default, and production.py will be specified in the wisgi.py default.