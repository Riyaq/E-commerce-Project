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
cur = mydb.cursor()<br><img width="1127" alt="SS" src="https://github.com/user-attachments/assets/187aab72-dbb3-4bac-a5ca-8b76830bc78f">


