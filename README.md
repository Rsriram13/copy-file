# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.

### Step 2:
Open the existing file to read.

### Step 3:
Open the new file to write.

### Step 4:
Copy the contents from existing file to new file.

### Step 5:
Get the inputs from the user for existing file and new file. Call the function.

### Step 6:
End the program.
## PROGRAM:
```
#Python program for copying the contents from one file to another file.
#Developed by: Sriram R
#Register Number: 212223230215

def copy(fname, newfile):
    with open(fname, 'r')as fp:
        with open(newfile, 'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for new file: ")
copy(fname, newfile)
```
### OUTPUT:
![output](https://github.com/Rsriram13/copy-file/assets/145742823/edd2c242-19fa-4f8d-add5-cee92c5814ac)
### EXISTING FILE:
![output](https://github.com/Rsriram13/copy-file/assets/145742823/dbfdc2c5-739c-4c2c-b03c-67c528df1274)
### NEW FILE:
![output](https://github.com/Rsriram13/copy-file/assets/145742823/e2d35838-2c17-41e1-8f31-0d70e5d39253)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
