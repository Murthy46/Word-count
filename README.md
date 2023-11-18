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
```
## DEVELOPED BY: Sundaramurthy M
## REFERENCE NUMBER: 23010238
num_words =0
file1 = open("text.txt", "r")
with open('text.txt','r') as file1:
    for i in file1:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```
#textfile
```python
with open("text.txt",'w')as fp:
  fp.write("Hello World")
  fp.write("\nWelcome to Python")
  fp.write("\nHave a Good Day")
```
### OUTPUT:
<img width="660" alt="Screenshot 2023-11-18 at 10 12 33 AM" src="https://github.com/Murthy46/Word-count/assets/145112768/412ed4e7-433c-4234-bd76-7d6c3ec83b3b">




## RESULT:
Thus the program is written to find the word count from a text.
