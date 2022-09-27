import sys

# add your project directory to the sys.path
project_home = u'/var/www/main.py'
if project_home not in sys.path:
    sys.path = [project_home] + sys.path

# import flask app but need to call it "application" for WSGI to work
from main import app as application  # noqa