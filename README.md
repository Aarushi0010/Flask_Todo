Don't worry you don't have to read this silly readme , it's just for my future references ! <br><br>

1. Initialize virtual environment in your project folder so all the the installed stuff stays in this envronment only . <br> cmd : pip install virtualenv <br>
2. Renmame the virtual env using cmd : virtualenv "env_name" and also activate it using comd : <br> env\Scripts\Activate [For windows] <br>
3. Now install Flask in this virtual env using cmd : pip install flask <br>
4. To run the application , use cmd : python app.py <br>

Database <br>
For database we are using SQLAlchemy which is a Python SQL toolkit <br>
To install cmd : pip install flask-sqlalchemy [inside virtual env] <br>
Now a very serious thing for adding database <br>
1. Don't forget to import database ie. from flask_sqlalchemy import SQLAlchemy <br>
2. we need two configurations , one for uri and the other for track_modifications <br>

Accepting responses using "submit" button : <br>
1. Fisrtly import request in app.py <br>
2. Make the button accept responses <br>
3. Add the nethods on the app.route <br>
4. Ensure it is working using an if statement to print the response in console <br>

Added the CRUD operations as well ! Let's see <br>
1. create - used the submit button and the POST method in app.py main function <br>
2. Read - used the GET method in main function and also displaying the new Todo in the list <br>
3. Update and Delete - added refernce for s.no and also redirected to refreshed page <br>
