# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0
### Step 2: 
open it with txt file
### Step 3: 
Give range for i
### Step 4:  
Then nxt split the words
### Step 5: 
count the number of words
### Step 6: 
Giving print statement for getting output

## PROGRAM:
num_words =0

with open('sample.txt','r') as file1:

  for i in file1:
 
  word =i.split()
 
  num_words += len(word)

print("Number of words={}".format(num_words))
### OUTPUT:
![screenshot](https://github.com/anushanirudh/Word-count/assets/151725737/31c47f4d-2bc0-4410-9210-d464aa8bf930)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
