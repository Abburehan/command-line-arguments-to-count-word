# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module.
### Step 2: 
 Open the file with sys.argv[1].
### Step 3: 
Use the for loop to select the content in file.
### Step 4:  
Use split function to to separate the file content into words or strings.
### Step 5: 
Count the length of the words using len.
### Step 6: 
Print the number of words.
## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: Abbu Rehan
RegisterNumber: 23010259

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```
### OUTPUT:
![Screenshot (160)](https://github.com/Abburehan/command-line-arguments-to-count-word/assets/138849336/9b5e7be2-fe68-4dd2-b2aa-f453df587f49)

![Screenshot (161)](https://github.com/Abburehan/command-line-arguments-to-count-word/assets/138849336/af3361e8-23fd-4035-a95e-a1761ce523d9)

![Screenshot (162)](https://github.com/Abburehan/command-line-arguments-to-count-word/assets/138849336/f0079273-9a40-493e-be9a-56027db6ff46)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
