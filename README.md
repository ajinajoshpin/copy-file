# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the source file in read mode.

## Step 2:
Read the contents of the source file and store it in a variable

## Step 3:
Close the source file.

## Step 4:
Open the destination file in write mode. If the file doesn't exist, it will be created.

## Step 5:
Write the contents from the variable to the destination file.

## Step 6:
Read the contents of the destination file and print it to verify the copy operation.

## Step 7:
End the program

## PROGRAM:
'''

#Python program for copying the contents from one file to another file.

#Developed by:ajina joshpin

#RegisterNumber:23013547

'''

 def copy(fname, newfile):

   with open(fname, 'r')as fp:

      with open(newfile, 'w') as fp1:

         data1=fp.read()

         fp1.write(data1)

 fname=input("Enter an existing file: ")

 newfile=input("Enter a name for new file: ")

 copy(fname, newfile)


### OUTPUT:
![Screenshot 2024-01-02 150522](https://github.com/ajinajoshpin/copy-file/assets/148514578/27e8cf48-bcd1-4ec1-8901-31f6503994de)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
