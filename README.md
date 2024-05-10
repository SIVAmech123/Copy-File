# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
First we need to open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.

# Step 2:
Using keyword "with" to open the requied file.

# Step 3:
Again using the with keyword to open the empty file.

# Step 4:
The empty file is open by using 'W' which is used to write only.

# Step 5:
The four function is used to take each line from the main file.


## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: SIVAKUMAR.R
#Register Number: 212223230209
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
### OUTPUT:
![Screenshot 2024-05-10 185246](https://github.com/SIVAmech123/Copy-File/assets/151629067/92d179a0-f61b-44cf-b3ba-5b2994ebddf7)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
