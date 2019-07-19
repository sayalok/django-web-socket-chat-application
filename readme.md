This is a simple chat application using channels details desciptions link down below

https://channels.readthedocs.io/en/latest/tutorial/

Project Setup/ Install
<ul>
<li> mkdir ***folder_name*** </li>
<li> cd ***folder_name*** </li>
<li> virtualenv . </li>
<li> source bin/activate # to activate virtual environment</li>
<li> pip3 install django</li>
<li> now clone the project here</li>

the strcture should be look like this
<pre>
--> bin
--> include
--> lib
--> local
--> src
	--> chat
	--> chatApp
	--> db.sqlite3
	--> manage.py
</pre>
<li> docker run -p 6379:6379 -d redis:2.8</li>
<li> pip3 install channels_redis</li>
<li> python3 manage.py runserver</li>
</ul>
