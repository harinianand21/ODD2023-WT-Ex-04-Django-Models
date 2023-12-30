# Ex-04-Django-Models

# NAME:HARINI.A
# REFERENCE NUMBER:23001688
# Department:CSE


# AIM:
To create django model

# DESIGN PROCEDURE
Django models

step 1: Create django project and app using the following commands
django-admin startproject mymodels
python manage.py startapp myApp

step 2:
create a user_profile models in model.py

![Screenshot 2023-12-30 181107](https://github.com/harinianand21/ODD2023-WT-Ex-04-Django-Models/assets/145742813/72edca28-136f-4d2c-8d31-8f4cabc398fc)

  
add the models in the admin interface using the code admin.py

![Screenshot 2023-12-30 181120](https://github.com/harinianand21/ODD2023-WT-Ex-04-Django-Models/assets/145742813/88f4910b-7bf9-435e-9eb5-8494105cb2a7)


write the function based view to render the data from the models to the template in views.py

![Screenshot 2023-12-30 181135](https://github.com/harinianand21/ODD2023-WT-Ex-04-Django-Models/assets/145742813/928a8563-ff8e-43cc-a3ad-853dd2752459)


set up the url path for the templates using urls.py

![Screenshot 2023-12-30 181143](https://github.com/harinianand21/ODD2023-WT-Ex-04-Django-Models/assets/145742813/699f1d4e-549b-48c4-aeb9-69fccb834980)

in settings.py file add the appcreated

step 3: Now do the migrations process to initiate and save the models

python manage.py makemigrations 
python manage.py migrate
create a template as user_profile.html

![Screenshot 2023-12-30 181153](https://github.com/harinianand21/ODD2023-WT-Ex-04-Django-Models/assets/145742813/59793243-6589-4737-b121-38d5511a67c8)


step4:
Run the program using the following command

python manage.py runserver 8000
in the admin page you can view the models created
and in the user_profile template page you can see the profile page of the user
# Output
![WhatsApp Image 2023-12-30 at 18 51 21_59645743](https://github.com/harinianand21/ODD2023-WT-Ex-04-Django-Models/assets/145742813/da7e1cdc-66ba-4c85-93de-f491d3ce7975)
![WhatsApp Image 2023-12-30 at 18 58 17_2cba4098](https://github.com/harinianand21/ODD2023-WT-Ex-04-Django-Models/assets/145742813/48a42124-b575-4bd8-831d-adf2eae7c3b7)


# Result:
Django model was created successfully
