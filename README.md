# Read-from-CSV

## AIM:
to develop a python program to read file from csv
## ALGORITHM:
### Step 1:
Import pandas module as pd.
### Step 2:
Using pd.read_csv() method read the CSV file.
### Step 3:
Using df.head() print the first 10 rows of the CSV file.
### Step 4:
Using df.tail() print the last 5 of the CSV file.
### Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for colum
## PROGRAM:
#Program to read contents from a CSV file.
#Developed by: Nirosha M
#RegisterNumber: 23014438
import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
## OUTPUT:
![Screenshot 2023-12-29 124658](https://github.com/niroshamuthukumar/Read-from-CSV/assets/151830921/2cfd9f70-e59d-4aae-b49d-64d5494c71c3)
## RESULT:
Thus the program is executed successfully
