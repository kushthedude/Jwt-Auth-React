# Jwt-Auth-React

### App created for Zigway.co

## Steps To Install:

### React Frontend :
- Clone the Repository.
- Go to `/Jwt-Auth-React/FE`
- Run `npm install`
- Run `npm start`

### Django Server:
- After successfully executing the FrontEnd steps, Navigate to `/Jwt-Auth-React/backend`
- Create a Virtual Env by `virtualenv -p python3 venv`
- Activate it by `source venv/bin/activate`
- Run `pip3 install -r requirements/local.txt`
- Now run `python manage.py makemigrations custom_user`.
- After creating `custom_user`, Run `python manage.py migrate`
- Now create a superuser by `python manage.py createsuperuser`
- Enter credantials for `SuperUser`.
- If everything goes well, You can start server by `python manager.py runserver`

#### Visit the app on `http://localhost:3000/`
