Iniciar o projeto Django

'''
py -m venv venv
venv\Scripts\acrivate
pip install django
django-admin startproject project .
py manage.py startapp contact
'''

Configurar o git

'''
git config --global user.name 'Seu nome'
git config --global user.email 'seu_email@gmail.com'
git config --global init.defaultBranch main
git init
git add .
git commit -m 'Mensagem'
git remote add origin URL-do-git
'''

Migrando a base de dados do Django

'''
py manage.py makemigrations
py manage.py migrate
'''

Criando e modificando a senha de um super usuário Django

'''
py manage.py createsuperuser
py manage.py changepassword USERNAME
'''
