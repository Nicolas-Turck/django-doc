## tuto django

# rapel commande

- Création de projet

$ django-admin startproject mysite

- Lancement serveur

§ python manage.py runserver

- Création application polls

§ python manage.py startapp polls

# base de données

- Création de tables

§ python manage.py migrate

- Inclure application polls

§ python manage.py makemigration polls

# Lancer shell Python

§ python manage.py shell

# Création compte administrateur

- Création utilisateur

§ python manage.py createsuperuser

Saisissez le nom d’utilisateur,  saisir l’adresse de courriel,  saisir le mot de passe

# Lancement de Tests

$ python manage.py test polls

