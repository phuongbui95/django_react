Django React Tutorial: https://blog.logrocket.com/using-react-django-create-app-tutorial/

1. Create a python venv:
python3 -m venv name_venv

2. Activate bin file:
source ./name_venv/bin/activate

3. Install Django, Django Rest Framework and Django CORS:
pip install django djangorestframework django-cors-headers

4. Create our API project — remember that you must be inside the venv:
django-admin startproject django_react_proj

5. When create a django in django project, make sure that the app is created inside the project's root so that manage.py can identify your alls to activate