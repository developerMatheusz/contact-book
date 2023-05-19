Iniciar o projeto Django

```
python -m venv venv
source venv/bin/activate
pip install django
django-admin startproject core
python manage.py startapp contact
```

Configurar o git

```
git config --global user.name 'My name'
git config --global user.email 'myemail'
git config --global init.defaultBranch main
git init
git add .
git commit -m "your message"
git remote add origin URL_DO_GITHUB
```

Migrando a base de dados do Django

```
python manage.py makemigrations
python manage.py migrate
```

Criando e modificando a senha de um super usuário Django

```
python manage.py createsuperuser
python manage.py changepassword [your username]
```