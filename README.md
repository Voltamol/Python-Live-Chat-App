# Python-Live-Chat-App
Uses Flask Sockets to create a live chat room application.


server command: gunicorn --worker-class gevent --worker-connections 1000 main:app