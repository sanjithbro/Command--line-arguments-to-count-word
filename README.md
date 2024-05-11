![image](https://github.com/sanjithbro/Command--line-arguments-to-count-word/assets/167451460/9251bdd5-e46e-49ae-84e0-b6be809c6525)# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module to use command line arguments.`

### Step 2: 
 Create a file pointer and open the file which is passed in command line.

### Step 3: 
Initialize word count as zero.

### Step 4:  
For each line in file, split it into words and find number of the words in every line.

### Step 5: 
Sum the number of words in each line.

### Step 6: 
Display the total words in the file.

## PROGRAM:
```python
Developed by: R.Sanjith
Register no: 212223230191
import sys
count=0
with open (sys.argv[1]) as f1:
   for line in f1:
      word=line.split()
      count+=len(word)
print("Total no of words in file is",count)
```
### OUTPUT:
![Uploading 329762254-b7c41b16-2366-449f-9cb8-cc382d60a5fd (1).jpg…]()

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
