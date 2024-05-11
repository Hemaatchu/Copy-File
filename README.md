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
Program for copying the contents from one file to another file
Developed by: HEMAVATHY.S
RegisterNumber: 212223230076
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)

```

### OUTPUT:
![WhatsApp Image 2024-05-11 at 6 31 37 PM](https://github.com/Hemaatchu/Copy-File/assets/147328300/71f8e24b-2988-4971-b0e9-31c3aa40215c)
![WhatsApp Image 2024-05-11 at 6 31 40 PM](https://github.com/Hemaatchu/Copy-File/assets/147328300/b89b34ac-26ce-443c-9668-20f5b83e0fe6)
![WhatsApp Image 2024-05-11 at 6 31 50 PM](https://github.com/Hemaatchu/Copy-File/assets/147328300/7f6de5ca-d25a-42c2-aad8-f1da0e815bb6)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
