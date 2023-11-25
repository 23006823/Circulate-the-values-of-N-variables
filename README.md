# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function named circulate.
### Step 2: 
Get a list input from the user.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
print the circulate value
### Step 6: 
Call the function using function call and end the program 
## Program:
~~~
#Program to circulate N values.
#Developed by: M GAYATHIRI ROSHINI
#RegisterNumber:23006823
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
~~~
## Output:
![image](https://github.com/23006823/Circulate-the-values-of-N-variables/assets/138971409/1e3a2f03-d346-4b21-b94e-5d070f6a1596)


## Result:
