Requirements (these requirements are my suggestion for easy setup of this php system): 
XAMPP server for windows
download XAMPP at https://www.apachefriends.org/index.html

Browser : Firefox/Chrome
#################################################################################
Setup Guide:
	SETUP XAMPP
1. Install XAMPP on your Windows Computer.
2. After Installing, go to the installation folder directory "C:\xampp\htdocs\".
3. In that directory extract contents of Assignment.rar.

	SETUP DATABASE
1. Open your browser and type on your address bar : "localhost/phpmyadmin". (without the quotation marks)
2. if login details are asked then just enter: 
username: root 
password: (don't enter anything here)
3. After logging in create a new blank database called "testdb" (again without the quotation marks).
4. After the database creation, a create table interface will show up. In here, click the IMPORT button.
5. Click Browse and find the testdb.sql file (it is also in the contents of the ASSIGNMENT.rar).
6. After selecting testdb.sql file simply click GO at the bottom to upload the tables into the testdb database.

	..AND WE'RE GOOD TO GO..
if you have extracted the contents of Assignment.rar inside the directory "C:\xampp\htdocs\" then
open your browser and type on your address bar : "localhost/assignment". (again without the quotation marks)

	HOW TO USE
This program pretty much explains itself at its main page. by default, it lists all the tasks with their taskid's.
just click the button "New Task" to create a new task name with its description.

On the list of tasks, simply click a task to see its details and when it was created or when it was last updated. 
Also, on the list of tasks, there is a corresponding Delete Link along the row of a single task.
