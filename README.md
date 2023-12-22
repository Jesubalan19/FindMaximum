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
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Jesubalan.A
RegisterNumber: 23013427
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```
''' 
''' 
Program to find the maximum marks using the list method max().
Developed by: Jesubalan.A
RegisterNumber: 23013427
'''
def max_marks(marks):
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: Jesubalan.A
RegisterNumber: 23013427
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max = i
    return max



```

## Output:

i)![Ex 3a i](https://github.com/Jesubalan19/FindMaximum/assets/144979294/d5ede736-542c-41fe-97e7-a01854544eb4)

ii)![Ex 3a ii](https://github.com/Jesubalan19/FindMaximum/assets/144979294/9b5dc175-1ef3-4371-9003-b0a920a9d584)

iii)![Ex 3a iii](https://github.com/Jesubalan19/FindMaximum/assets/144979294/85e73749-e7f3-4698-8ea6-4e406244a6cb)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
