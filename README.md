# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
```python
'''
Program to count the no. of words in a file.
Developed by: B KRISHNAKANTH
Reg.no: 212223230109
'''
fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)
```

### OUTPUT:

![image](https://github.com/Krishnakanth23006762/Word-count/assets/138849446/b48e8e75-e480-466f-b3e0-f9af2b6a88ea)


## RESULT:
Thus the program is written to find the word count from a text.
