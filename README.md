# DATE:
# EXP.NO:11
# Copy-File
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
##Developed By: RUDESH KANNA R
##Reg No: 24900303
```
with open("text1.txt",'r') as fp:
  msg1=fp.read()
with open("copytxt",'w') as fp1:
  fp1.write(msg1)
```
### OUTPUT:
![331259946-b51983bc-395f-4f12-89b2-82fd31f00cc4](https://github.com/user-attachments/assets/6a0eff4d-421a-4f44-913d-41ada863f852)
![331260713-80f71b4c-454e-44f3-9835-fc677d198c8b](https://github.com/user-attachments/assets/641431e3-8473-49b3-bf6e-102333dd54e1)
![331260544-c14ba149-48db-4aef-9ce0-8207ba1271b9](https://github.com/user-attachments/assets/df2f3907-02cf-466a-b5f8-fc90f2ab74d2)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
