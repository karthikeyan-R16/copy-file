# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
#Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

#Step 2:
Read the file and store in a variable.

#Step 3:
Now create a new file in which we want to paste the content using write access mode.

#Step 4:
Use write function to copy the read file that has been stored in the variable.

#Step 5:
The content in the original file will be copied in the new file.

#Step 6:
End the program.


## PROGRAM:
```
Developed by: Karthikeyan R
RegisterNumber: 212222240045

with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
 ```           
### OUTPUT:

![image](https://github.com/karthikeyan-R16/copy-file/assets/119421232/3bd7d7f6-bd38-4ead-9f55-3aeba18bdc42)

![image](https://github.com/karthikeyan-R16/copy-file/assets/119421232/3a76e5d8-f3eb-4fed-a010-e050342c0633)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
