Project Setup/ Install

1. mkdir ***folder_name***
2. cd ***folder_name***
3. virtualenv .
4. source bin/activate # to activate virtual environment
5. pip3 install django
6. now clone the project here

the strcture should be look like this
   --> bin
   --> include
   --> lib
   --> local
   --> src
       --> chat
       -->chatApp
       --> db.sqlite3
       --> manage.py


7. docker run -p 6379:6379 -d redis:2.8
8. pip3 install channels_redis
9. python3 manage.py runserver
