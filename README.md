# E-commerce-Project


import pandas as pd<br>
import matplotlib.pyplot as plt<br>
import seaborn as sns<br>
import mysql.connector<br>








**To establish connection taing a variable as mydb**<br>
mydb = mysql.connector.connect(host="localhost", <br>
                               username="root",<br>
                               password="**********",<br>
                               database="ecommerce")<br>
<br>
**Lets activate the cursor**<br>
cur = mydb.cursor()<br>
![Uploading Screenshot 2024-08-06 at 1.33.55 AM.png…]()
