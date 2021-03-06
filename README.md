
# Bookshelf

**Bookshelf** is a website that was my final project for CS50X 2018.

## Used in the creation of this website
* [Python](https://www.python.org/)
* [Javascript](https://www.javascript.com/)
* [jQuery](https://jquery.com/)
* [Bootstrap](https://getbootstrap.com/)
* [Goodreads](https://www.goodreads.com/)

## Dependencies 
- **flask**
- **flask-session**

## Geting started

**_NOTE: If you don't have git, just download the zip file. (skip this step)_**

##### Clone the repository and move into its directory
```
$ git clone https://github.com/Minter27/Bookshelf.git 
$ cd Bookshelf
```

### Installing dependencies

*Please use `pip`*
###### Windows
```
$ pip install flask flask-session
```
###### Mac OS/Linux
```
$ pip3 install flask flask-session
```

### Launching the server

##### Change lines `36` and `37` in `application.py` to the email and password you wish to run the `SMTP` server on. (the email to send the emails from)
```
...
36 | myEmail = yourEmail
37 | myPassword = yourPassword
...
```
#### Set flask app to `application.py`
###### Windows
```
$ set FLASK_APP=application.py
```
###### Mac OS/Linux
```
$ export FLASK_APP=application.py
```
##### Launch the server
```
$ flask run
```

## IMPORTANT
In order for your newly created account to be able to send emails on your behalf (and allow this application to run), you will likely need to allow 'Less secure app access' on your new gmail account as described [here](https://support.google.com/accounts/answer/6010255?hl=en).
