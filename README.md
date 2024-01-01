# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a text1.txt with some content in it

### Step 2: 
open the text1.txt file in read mode
 
### Step 3: 
create a copy.txt file using write mode 

### Step 4: 
copy the content of text1.txt file to copy.txt using write function

## PROGRAM:

with open("text1.txt",'r')as fp:

     msg1=fp.read()
     
  with open("copytxt",'w')as fp1:
  
     fp1.write(msg1)

### OUTPUT:
![Screenshot 2024-01-01 131013](https://github.com/23004345/copy-file/assets/138849203/38274811-73cb-4b8f-aa3c-6132e5ea837d)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
