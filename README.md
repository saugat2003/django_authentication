# Django Authentication System  

This is a simple system for user sign-up, login, and logout using Django.  

## Features  
- Users can sign up.  
- Users can log in and log out.  
- Passwords are safely stored.  
- Keeps users logged in with session management.  

## What You Need  
Before using this project, make sure you have:  
- Python 3.x installed  
- Django installed  

To install Django, run this command:  
```bash
pip install django
```  

## How to Use  
1. Get the project by cloning the repository or creating a new Django project:  
   ```bash
   django-admin startproject django_auth  
   cd myproject  
   ```  
2. Make a new app for authentication:  
   ```bash
   python manage.py startapp accounts  
   ```  
3. Add `authentication` to `INSTALLED_APPS` in `settings.py`.  
4. Create user models, views, and templates for login, sign-up, and logout.  
5. Apply database changes:  
   ```bash
   python manage.py migrate  
   ```  
6. (Optional) Create an admin user:  
   ```bash
   python manage.py createsuperuser  
   ```  
7. Start the server:  
   ```bash
   python manage.py runserver  
   ```  
8. Open `http://127.0.0.1:8000/` in your browser to use the system.  

## Handling Errors  
- Checks user input before saving.  
- Shows clear error messages if login or sign-up fails.  

## License  
You can use this project for free under the MIT License.  
