# django_commands

-----------------------------------------------------------------
||    01110100 01100001 01101001 01100111 01100101             ||
=================================================================

		INIT A NEW PROJECT IN VSCODE CMD

=================================================================
python -m venv .venv
.venv\Scripts\activate.bat
pip install django==4.0
pip install djangorestframework==3.13.0
pip install markdown       
pip install django-filter  
django-admin startproject django_project .
pip freeze > requirements.txt
echo. > README.md
copy D:\codes\django\.gitignore .
git init
git add .
git commit -m "first commit message created from txt file"
py manage.py runserver


__________________________________________________________________
------------------------------------------------------------------
__________________________________________________________________



=================================================================

		Deply to python anywhere
/home/carbonahs/django_pythonanywhere
/home/carbonahs/.virtualenvs/test_env
=================================================================
git clone <repo link>
python3 -m venv env 
source env/bin/activate 
cd <repo folder>
pip install -r requirements.txt 


mkvirtualenv --python=/usr/bin/python3.8 test_env
source test_env/bin/activate



=================================================================

		Model Class Imports

=================================================================

from django.db import models
from django.urls import reverse
from django.utils.translation import gettext_lazy as _

*****************************************************************

			random commands

*****************************************************************
django-admin startproject

py manage.py runserver
py manage.py runserver 0.0.0.0:8000

py manage.py startapp 


py manage.py makemigrations
py manage.py migrate

py manage.py createsuperuser
carbon-ahs
shehanuk.ahsan@gmail.com
1234
1234
y


pip install whitenoise==6.0.0
pip install django-cors-headers==3.10
python manage.py showmigrations
python manage.py migrate --fake <app_name> zero

pip install dj-rest-auth==2.1.11
pip install django-allauth==0.48.0
pip install drf-spectacular==0.21.0
pip install django-debug-toolbar
pip install mysqlclient

python manage.py showmigrations

python manage.py migrate --fake admin zero
python manage.py migrate --fake auth zero
python manage.py migrate --fake contenttypes zero
python manage.py migrate --fake sessions zero

python manage.py showmigrations

python manage.py migrate admin zero
python manage.py migrate auth zero
python manage.py migrate contenttypes zero
python manage.py migrate sessions zero

git commit -m "
=================================================

==================================================

git remote add origine <repo_link>
git pull origine
git checkout <branch_name>
==================================


