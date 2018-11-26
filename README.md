# Weather-App-using-Django
Weather Web based App using Django
## Lets Get Started

### Go the Project Folder and Write Following Commands

> django-admin startproject the_weather

>>cd the_weather 

>>python3 manage.py runserver
#### If you look at your terminal, you should see the URL for your app. By default it should be 127.0.0.1:8000.
>Open up your browser and go to that URL.

##### The Admin Dashboard

Next we want to take a look at the admin dashboard Django gives us. To do that, first we have to migrate our database, which means Django will create the pre-defined tables that are needed for the default apps. To do this, you simply run the migrate command. Stop the server by using CTRL+C and then run:
>> python3 manage.py migrate


By running that command, Django has created a SQLite database for you, the default database in the settings, and it has added several tables to that database. You'll know if the database was created if you see a new db.sqlite3 file in your project directory.
One of the tables Django gives us is a user table, which will be used to store any users in our app. The app we're building doesn't need any users, but having an admin user will allow us to access the admin dashboard.
To create an admin user, we'll run the createsuperuser command.


>>python3 manage.py createsuperuser
<p>
Follow the instructions by giving a username, email address, and a password for your admin user. Once you've done that, you'll need to start the server again and navigate to the admin dashboard.

</p>

>>python3 manage.py runserver

<p>
Then go to 127.0.0.1:8000/admin.

The reason why we can go to this page is because because admin is set up in our urls.py (the reason why we can see the congratulations page is because Django gives you that until you add your own URLs).
</p>


<p>
  After Adding the cities in Admin panel Visit 127.0.0.1:8000 to see the App working..
  </p>
  
