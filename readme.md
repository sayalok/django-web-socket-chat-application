Project Setup/ Install
<ul>
<li>1. mkdir ***folder_name*** </li>
<li>2. cd ***folder_name*** </li>
<li>3. virtualenv . </li>
<li>4. source bin/activate # to activate virtual environment</li>
<li>5. pip3 install django</li>
<li>6. now clone the project here</li>

the strcture should be look like this
<pre>
--> bin
--> include
--> lib
--> local
--> src
	--> chat
	-->chatApp
	--> db.sqlite3
	--> manage.py
</pre>
<li>7. docker run -p 6379:6379 -d redis:2.8</li>
<li>8. pip3 install channels_redis</li>
<li>9. python3 manage.py runserver</li>
</ul>
