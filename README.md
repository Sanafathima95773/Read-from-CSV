# Read-from-CSV

## AIM:
To write a python program for reading the csv file content

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
Developed by: Sana Fathima H Register number: 212223240145
```
import pandas as pd
df=pd.read_csv("NBA.csv")
print(df.head(10))
print(df.tail())
print("No of rows",len(df.axes[0]))
print("No of coloumn",len(df.axes[1]))
```

## OUTPUT:
![Screenshot 2024-05-17 191826](https://github.com/Sanafathima95773/Read-from-CSV/assets/147084627/261bf690-d056-45b8-9447-06eea50f3750)


## RESULT:
