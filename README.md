# web
 ## Using if pipenv and python 3.6 is installed
 
```
$ git clone <repo url>

$ pipenv install

$ cd csea_events

$ python manage.py runserver

//then go to - "http://localhost:8000" on the browser

```

## If pipenv or python 3.6 isn't installed (or any other problem come up)

```
$ pip install requests django

$ git clone <repo url>


$ cd csea_events

$ python manage.py runserver

//then go to - "http://localhost:8000" on the browser
```

## Warning

Do not open the page by entering 127.0.0.1, it's effectively same as localhost but microsoft will block it because of not having https

## Warning II

The repo contain hard coded production secret, outlook OAuth secret key and App registration details. It's a terrible practice and will be changed later
