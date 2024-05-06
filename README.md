# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest.
### Step 2: 
 On the same location as the text file, create a python program file.
### Step 3: 
In python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4:  
using read() and split(), split the lines in the file into a sequence of words
### Step 5: 
using len() count the number of words in the text file
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output
## PROGRAM:
```
# Python program for getting the word count from the contents of a file using command line arguments.
# Developed by: KEERTHIVASAN M
# Register number: 212223100021
import sys
count = 0
with open(sys.argv[1],'r')as f1:
    for line in f1:
        word = line.split()
        count += len(word)
print("word count in file = ",count)
```
### OUTPUT:


![image](https://github.com/rdxkeerthi/Command--line-arguments-to-count-word/assets/147473120/b7cd1aa4-f2e2-42d6-9caa-278dc3755bdd)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
