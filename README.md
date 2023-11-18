# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
start the program
### Step 2: 
prepare the list from the each linear equation and assign in np.array().
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
add coding to the input value.
### Step 6: 
print coding to get the answer
## Program:
```
#Program to circulate N values.
#Developed by: Moulidhar.G
#RegisterNumber:23009285
def circulate():
    l1=eval(input())
    n=int(input())
    d=l1[n:]+l1[:n]
    print("After circulating the values are:",d)
```

## Output:
![image](https://github.com/moulidharyadav/Circulate-the-values-of-N-variables/assets/147078316/1c7022ab-9c01-4803-bd0b-85d19404b82b)
## Result:
program executed
