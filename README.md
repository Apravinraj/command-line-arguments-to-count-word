# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module

### Step 2:
Open the file with sys.argv[1]

### Step 3:
Use the for loop to select the content in file

### Step 4:
Use split function to to separate the file content into words or strings

### Step 5:
Count the length of the words using len

### Step 6:
Print the number of words

## PROGRAM:
```
Developed by: Pravin aj.A
RegisterNumber: 212222240079
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("Number of words in a file",count)
```
### OUTPUT:
![image](https://github.com/Apravinraj/command-line-arguments-to-count-word/assets/118707879/3e2b7152-a42b-4269-9a62-8c4b0004f987)

![image](https://github.com/Apravinraj/command-line-arguments-to-count-word/assets/118707879/c3df192d-52cf-4eec-9005-322adecf82ed)

![image](https://github.com/Apravinraj/command-line-arguments-to-count-word/assets/118707879/7c535bdf-8d8c-442b-86c1-d19d619fd927)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
