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
![image](https://github.com/Bosevennila/FindMaximum/assets/144870486/a48de1b9-0018-4db6-bef6-726e535ba6dd)
![image](https://github.com/Bosevennila/FindMaximum/assets/144870486/0b1c7363-9117-41f1-bdcc-c6619e50a186)
![image](https://github.com/Bosevennila/FindMaximum/assets/144870486/a89d1e14-4e9e-4d3f-8f42-32183005ba34)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
