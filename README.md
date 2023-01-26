# Word-count

## AIM:

To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:

Open visual studio code

### Step 2: 

Create file with .py extension.
 
### Step 3: 

Start the program.

### Step 4:  

Write the code.

### Step 5: 

Run terminal for output of the given program

### Step 6: 

End the program

## PROGRAM:

```
'''
Developed by : Shriram S
Register Number : 22008494
'''
num_words = 0
with open('Text.txt','r') as f1:
    for i in f1:
        words=i.split()
        num_words+= len(words)
print("Number of words in the file = {}".format(num_words))
```


### OUTPUT:

#### Text File 

![shri 5a text](https://user-images.githubusercontent.com/117991122/214806204-b47bb3c0-2cf9-417d-a033-9ac0c4ad4fac.png)


#### Code

![SHRI 5A code](https://user-images.githubusercontent.com/117991122/214806320-f162a6eb-3034-4700-a34a-551b78a36a3a.png)


## RESULT:
Thus the program is written to find the word count from a text.
