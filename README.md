# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Create a user defined function
### Step 2: 
Get the variables from user to enter inside the list
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
After rotating the variables , store the rotated variables in a seperate list
### Step 6: 
At last , print the list of rotated variables
## Program:
```
#Program to circulate N values.
#Developed by:SRIVATSAN V 
#RegisterNumber:23000970
def circulate():
    l1=eval(input())
    a=int(input())
    l2=[]
    for i in range(a,len(l1)):
        l2.append(l1[i])
    for i in range(a):
        l2.append(l1[i])
    print("After circulating the values are:",l2)
```

## Output:
![Screenshot 2023-11-22 092033](https://github.com/Srivatsan0405/Circulate-the-values-of-N-variables/assets/139841630/40e26180-37d8-4111-9369-305391f0c057)


## Result:
