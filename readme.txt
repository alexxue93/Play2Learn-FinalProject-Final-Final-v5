SETUP: 
python -m venv .venv
.venv\Scripts\activate

Multiple installs: 
pip install -r requirements.txt 

VUE-GAMES:
npm install
npm run serve

Migrate:
python manage.py makemigrations
python manage.py migrate

RUN AT ROOT DIR:
python manage.py runserver


Create Super User:
python manage.py createsuperuser