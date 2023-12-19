# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: CHANDRAPRIYADHARSHINI C 
RegisterNumber:23013526 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: CHANDRAPRIYADHARSHINI C
RegisterNumber: 23013526
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
i) # To find the maximum of marks using the list method sort.
![image](https://github.com/Bosevennila/FindMaximum/assets/144870486/63797662-ff51-4ee0-8595-951d7afc142c)
ii) # To find the maximum marks using the list method max().
![image](https://github.com/Bosevennila/FindMaximum/assets/144870486/76ae8125-85b5-4a28-8682-eeaa2110bb11)
![image](https://github.com/Bosevennila/FindMaximum/assets/144870486/7bf2420a-9c4b-4e88-9045-61f8c96b5ea3)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
