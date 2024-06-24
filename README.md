# trendwave
 a social site, find whats trending
## Running this program
clone the program into your local repository
after clonning use the following command to install the necessary modules to handle different files
pip install -r requirements.txt 
### make migrations
python manage.py makemigrations or
python3 manage.py makemigrations
#### migrate
python manage.y migrate
or python3  manage.py migrate
##### you can create a superuser for this but it wont work since i added admin middleware 
make any user a superuser and isstaff through the database
-do the below after running server
login with the username and password with whom you have made isstaff and on the browser where your path name is or origin name is add /admin to navigate to admin page e...g http://1.2.7.0.0.1:8000/admin

###### runserver
python manage.py runserver
or python3 manage.py runserver

