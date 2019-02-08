# Chat-IO
An efficient multi-user Chat WebApp built with Django, Web Sockets, and Channels 2.

#### Basic System Prerequisites:
```
Python == 3.6
pip >= 18.1
virtualenv >= 16.0.0
```

#### Fork this repo and run these commands after cloning the project and go inside the directory:
```
virtualenv venv
source venv/bin/activate
pip3 install -r requirements.txt
python3 manage.py migrate
python3 manage.py runserver
```
#### TODOs:
- [ ] **Group Chat**
- [ ] Finding which user is currently **typing**
- [ ] User **Online / Offline**
- [ ] Finding out count of **messages unread** in a chat
