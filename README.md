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
with open("text.txt", "r") as fp:
    msg1 = fp.read()
with open("copy.txt","w") as fp1:
    fp1.write(msg1)

```
### OUTPUT:
![image](https://github.com/SIVAmech123/Copy-File/assets/151629067/b78bd4cf-d682-4115-96ac-3dd81711f00d)





## RESULT:
Thus the program is written to copy the contents from one file to another file.
