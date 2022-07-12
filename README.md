# SQL-queries
Driver for connectingpython with sql.

!pip install mysql-connector-python

import mysql.connector as connection


mydb = connection.connect(host="localhost",user="root", passwd="SQL pwd",use_pure=True,buffered=True)#use your sql password

 # check if the connection is established
 
 
query = "Create Database Carbon"

cur= mydb.cursor()          my curser wil point to 1st location

cur.execute(query)
