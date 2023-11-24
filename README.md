# Circulate-the-values-of-N-variables
# NAME:ABDULLAH
# REFERENCE NUMBER:23013613
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
using eval get inputs from the user


### Step 2:

store this eval values in l
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### step 5 
print those rotated list using print function

## Program:
``````

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
``````


## Output:

![Alt text](<Screenshot 2023-11-24 053943.png>)


## Result:
hence the output was sucessfully verified
