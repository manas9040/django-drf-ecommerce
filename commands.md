<!-- commands -->

# Packages
Django==4.1.2
djangorestframework==3.14.0
python-dotenv==1.0.0
pytest==7.4.0
pytest-django==4.5.2


<!-- TO GENERATE SECRET KEY -->
from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())

<!-- LOAD ENV FILE  -->
from dotenv import load_dotenv
load_dotenv()  # take environment variables from .env.
os.environ.get('')#set the constant present in .env file 

