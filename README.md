# flask-API

This is a simple python API server using Flask, Vue JS and MySQL. 


### Install

Clone repo

```bash

git clone https://github.com/ghost717/flask-API.git flask-API

```

Install server 

```bash

python -m venv env

#win
env\Scripts\activate 

#mac
source env/bin/activate 

pip install flask flask-cors flask-mysqldb flask-bcrypt flask-jwt-extended flask_login

```

Install client 

```bash

npm install -g @vue/cli@3.7.0

vue create client

```


### Run

Run serwer

```bash

python app.py

```

Run client

```bash

npm run serve

```


### Deployment client in Firebase 

- firebase config
```
firebase init
```

- build
```
npm run build
```

- deploy in firebase
```
firebase deploy --only hosting
```


### Source

- https://testdriven.io/blog/developing-a-single-page-app-with-flask-and-vuejs/
- https://www.codementor.io/adityamalviya/python-flask-mysql-connection-rxblpje73
- https://www.roytuts.com/python-web-application-crud-example-using-flask-and-mysql/
- https://code.tutsplus.com/tutorials/creating-a-web-app-from-scratch-using-python-flask-and-mysql--cms-22972
- deploy client https://www.youtube.com/watch?v=HqThxPmBGlI

### Wheel for MySQLdb

- https://www.lfd.uci.edu/~gohlke/pythonlibs/#mysqlclient