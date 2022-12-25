## Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm:
### Step 1: 
First step is to define the function
### Step 2: 
Get l,n input from the user
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print the result.
## Program:
```
#Program to circulate N values.
#Developed by:Vasanthamukilan 
#RegisterNumber:22001986
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
!['output'](/Screenshot_20221225_064622.png)
## Result:
Thus the Circulate the values of n variables is successfully
executed.