# Circulate-the-values-of-N-variables
# NAME:ABDULLAH R
# REFNO:23013613
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
define function circulate.

### Step 2:
Get input from the user for the list.

### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5:
Print  the result

### Step 6: 
Call the function circulate().
## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)

```

## Output:
![Alt text](<Screenshot 2023-11-26 000650.png>)
## Result:
Thus swapping of two values is executed sucessfully