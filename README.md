# Read-from-CSV

## AIM:
To write a python program for reading content from a csv file

## ALGORITHM:
### Step 1:
Import pandas as pd

### Step 2:
Read the CSV file using read_csv method

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len()method to get the number of rows and columns.

### Step 5:
Display the result.

## PROGRAM:
```
#program to copy contents from one file to another
# Developed by : Hariharan A
# Reg no : 212223110013

import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of row")
```

## OUTPUT:
![image](https://github.com/hariharana59/Read-from-CSV/assets/144980130/fe428833-6ac4-4f4c-b35b-5fcbcec24ad5)

## RESULT:
Thus python program for reading content from a CSV file is successful.
