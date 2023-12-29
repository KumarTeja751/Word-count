# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Instalize the value for count as zero
### Step 2: 
Using open command open the txt file to read
### Step 3: 
Use the split() command
### Step 4:  
print the counted words
### Step 5: 
End the program.
## PROGRAM:
```
'''
Developed by: NARAMALA KUMARTEJA
Registered number: 212223230132
'''
num_words=0
with open('cyber.txt','r') as f1:
    for i in f1:
        word=i.split()
        num_words += len(word)
print("Number of words in the file = {}".format(num_words))
```
### OUTPUT:
![image](https://github.com/KumarTeja751/Word-count/assets/144947756/cfc853c9-3089-4575-b631-748d47dad18c)
![image](https://github.com/KumarTeja751/Word-count/assets/144947756/63f9d112-da66-4158-832d-bd15042997bc)

## RESULT:
Thus the program is written to find the word count from a text.
