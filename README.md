# Cashcore
# Cashcore Edge

to create venv folder if you don have it in the folder structure:
pip install virtualenv
virtualenv env

or 

PREREQUISITE: 

1. (if venv file is not in folder structure or is corrupt) use this command:
        python -m venv venv #create venv dir

Prerequisite: Remember to always activate the virtual environment:
source venv/bin/activate # For mac/linux OS

Navigate to: PS D:\HDD\Desktop\Cashcore-main\cashcore-main\backend\
.\venv\Scripts\activate.ps1   #windows run virtual environmen

    Type: exit #to exit the virtual environment

Commands:
Navigate to: cd backend
1. pip install -r requirements.txt
2. cd server
3. pip install -r requirements.txt
4. pip install -r requirements.txt --upgrade --no-deps
5. Install Core application package dependencies:
    pip install python-dotenv 
    pip install djangorestframework 
    pip install djongo 
    pip install pytz 
    pip install --upgrade djangorestframework 
    pip install dnspython 
    pip install django-cors-headers
    pip install psycopg2
    pip install plaid-python

 ---For use with MongoDB and Django (experimental)---   
    pip install mongoengine
    pip install djongo pymongo


6. python manage.py runserver # run web server on localhost


TODO: 

1. Fix Postgres local Database Connection
2. Fix Plaid API Connection, or integrate new API
