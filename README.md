# Read-from-CSV

## AIM:
To write a python program to read data from CSV files.
## ALGORITHM:
### Step 1:
Start the python.

### Step 2:
Import pandas.

### Step 3:
Mention the CSV file which is to be read.

### Step 4:
Read the contents of the CSV file using df.read function.

### Step 5:
End the program.

## PROGRAM:
### Developed By:Ragul M
### Register number:21500303
~~~
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head())
print(df.tail())
print("Column",len(df.axes[0]))
print("Rows",len(df.axes[1]))
~~~

## OUTPUT:
![output](https://github.com/ragulmani936/Read-from-CSV/blob/main/Screenshot%20(59).png)

## RESULT:
