# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
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
```
# Program to find the word count using command line arguments
# Developed by : HEMAVATHY.S
# Register Number : 212223230076
with open("sys.txt",'r') as fp:
  msg  = fp.read()
with open("copytxt",'w') as fp1:
  fp1.write(msg)

```

### OUTPUT:
![WhatsApp Image 2024-05-10 at 7 53 01 PM](https://github.com/Hemaatchu/Copy-File/assets/147328300/cf782ab0-e40b-4bc6-86c3-138024d9afaf)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
