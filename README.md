# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Import sys

### Step 2: Open file using commandline arguments.
 
### Step 3: Using for loop find the word count from the contents of a file.

### Step 4: Use len to count number of words.

### Step 5: Give print statement.

### Step 6: End the program.

## PROGRAM:
```
#Developed by: K.SANTHANA LAKSHMI
#Register num: 212222240091
num_words=0
with open('shara.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words += len(word)
print('num of words={}'.format(num_words))

``` 
### OUTPUT:
![image](https://github.com/santhanalakshmi04/command-line-arguments-to-count-word/assets/119475762/69936ff6-c0c9-4e3b-990e-18f063e3dd82)

![image](https://github.com/santhanalakshmi04/command-line-arguments-to-count-word/assets/119475762/8801b0a4-d403-49dd-8986-1a9bcf48a5cf)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
