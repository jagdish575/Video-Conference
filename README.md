#first create a venv
python -m venv venv
#activate venv 
venv/scripts/activate
#install requirements.txt
pip install -r requirements.txt
#go to project path
cd ./poject
run python manage.py makemigrations
run python manage.py migrate
python manage.py runserver


