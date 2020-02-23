# SecureApp
Our MOST secure app. Made for a school project

# Set Up:
 1. `git clone https://github.com/AnttiRae/SecureApp.git` clone this repo
 2. `cd SecureApp` 
 3. `python3 -m venv env` make a virtual enviroment for all the packages to be installed
 4. `source env/bin/activate` start the virtual enviroment
 5. `cd SecureApp`
 6. `pip install -r requirements.txt` install needed python packages
 7. `python manage.py migrate` apply migrations to db (sqlite3 (tää voidaan vielä vaihtaa johonki muuhun jos halutaan))
 8. `python manage.py runserver` start the server

# Requirements
  python 3.6+
  
  requirements.txt:
  ```
  astroid==2.3.3
  Django==2.2.7
  isort==4.3.21
  lazy-object-proxy==1.4.3
  mccabe==0.6.1
  pylint==2.4.3
  pytz==2019.3
  six==1.13.0
  sqlparse==0.3.0
  typed-ast==1.4.0
  wrapt==1.11.2
```
