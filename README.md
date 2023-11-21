# EX-04- Django-Models
# NAME: SANDHIYA P
# REFERENCE NUMBER: 23012555
# DEPARTMENT: AIDS

# AIM: 
    TO create django model

# DESIGN PROCEDURE:

Django models

Step1 : Create django project and app using the following commands:
           Django-admin startproject mymodels
           Python manage.py startapp myapp

Step 2: create a user_profile models in model.py

![WhatsApp Image 2023-11-21 at 20 22 30_e39d21e3](https://github.com/Sandhiyapalanivel/ODD2023-WT-Ex-04-Django-Models/assets/145743091/a35c88b7-daa1-4506-9648-a7d21b30dc88)


Add the models in the admin interface using the code in admin.py


![WhatsApp Image 2023-11-21 at 20 22 30_4c77db03](https://github.com/Sandhiyapalanivel/ODD2023-WT-Ex-04-Django-Models/assets/145743091/eca1f728-8f98-439e-8ab8-0d2b3507cf9b)

Write the function based view to render the data from the models to the template in
view.py

![WhatsApp Image 2023-11-21 at 20 39 47_2ad851b7](https://github.com/Sandhiyapalanivel/ODD2023-WT-Ex-04-Django-Models/assets/145743091/ab9455bd-11c2-46b6-85ea-f0f392d4a0ed)


Setup the url path for the templates using urls.py

![WhatsApp Image 2023-11-21 at 20 22 30_b02e9657](https://github.com/Sandhiyapalanivel/ODD2023-WT-Ex-04-Django-Models/assets/145743091/3151af28-74d7-4016-aa53-16ca93471448)



In settings.py file add the app created.

Step 3:
       Now do the migrations process to initiate and save the models
          Python mange.py makemigrations
          Python manage.py migrate

![WhatsApp Image 2023-11-21 at 20 22 30_662a151a](https://github.com/Sandhiyapalanivel/ODD2023-WT-Ex-04-Django-Models/assets/145743091/326aba8f-a729-4802-94bb-929f027cd434)


Last step: run the program using the command
           Python manage.py runserver 8000
           
In the admin/ page you can view the models created
And in the user_profile template page you can see the profile page of the user.

# OUTPUT:

![image](https://github.com/Sandhiyapalanivel/ODD2023-WT-Ex-04-Django-Models/assets/145743091/2562c347-f9b2-40eb-8766-a79fc02460b4)

![image](https://github.com/Sandhiyapalanivel/ODD2023-WT-Ex-04-Django-Models/assets/145743091/fc7b1f02-e909-4921-8ecc-68ac0de224bb)





