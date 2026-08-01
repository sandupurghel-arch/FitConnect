open fitconnect folder. right click and open terminal and run these commands one by one:

python -m venv venv

Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

venv\Scripts\activate

 pip install -r requirements.txt

python manage.py makemigrations ; python manage.py migrate

python manage.py runserver	

http://127.0.0.1:8000/