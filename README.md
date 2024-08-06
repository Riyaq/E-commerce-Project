# E-commerce-Project


import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import mysql.connector


#To establish connection taing a variable as mydb.
mydb = mysql.connector.connect(host="localhost", 
                               username="root",
                               password="Riya",
                               database="ecommerce")

#Lets activate the cursor.
cur = mydb.cursor()
