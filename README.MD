Set-up Django Application

python3.11 -m ensurepip
python3.11 -m pip install Django
django-admin startproject <Name of project>

cd <Name of project>

python3.11 manage.py migrate
python3.11 manage.py runserver


--

python3.11 manage.py makemigrations customer360
python3.11 manage.py migrate
python3.11 manage.py runserver