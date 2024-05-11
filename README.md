# Command--line-arguments-to-count-word
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
   for line in f!:
      word=line.split()
      count+=len(word)
print("Total no of words in file is",count)
```
### OUTPUT:
![329142176-ad25f8bc-2999-4f4f-9ad0-1059e7366a0a](https://github.com/sanjithbro/Command--line-arguments-to-count-word/assets/167451460/280add20-609f-47f9-85ef-7921d43422ce)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
