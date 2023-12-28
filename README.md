# Read-from-CSV

## AIM:
Write a program to read a csv file.
## ALGORITHM:
### Step 1:
Import pandas module as pd
### Step 2:
Read a csv file name cars.csv 
### Step 3:
print the first five rows and last five rows
### Step 4:
print the length of the rows and columns
### Step 5:
End the program

## PROGRAM:
```
"""write a program to read a csv file
Developed by :AADITHYA R
Reference no:23006361
"""
import pandas as pd
df=pd.read_csv("cars.csv")
print(df.head())
print(df.tail())
print("Rows",len(df.axes[0]))
print("Columns",len(df.axes[1]))
```

## OUTPUT:
![Screenshot 2023-12-28 155730](https://github.com/Aadithya2201/Read-from-CSV/assets/145917810/65947c3a-5345-4359-8e13-f157381e8bef)

![Screenshot 2023-12-28 155750](https://github.com/Aadithya2201/Read-from-CSV/assets/145917810/0631f170-0355-4d3a-ac5e-cd17a0b93642)


### i)CSV FILE
![Screenshot 2023-12-28 155804](https://github.com/Aadithya2201/Read-from-CSV/assets/145917810/b53ad889-90aa-4a33-8b3b-2d7ff8297c91)

## RESULT:
Thus the program is written to read a csv file.
