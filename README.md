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
Developed by:A.BHAGATH KRISHNA
RegisterNumber: 23002963
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
Developed by: A.BHAGATHKRISHNA
RegisterNumber: 23002963
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: A.BHAGATHKRISHNA
RegisterNumber: 23002963
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```
## Output:


![Screenshot 2023-12-29 094331](https://github.com/Bhagath118/FindMaximum/assets/147473779/6f662dea-3dac-4459-890c-bd5e1d8f1627)

![Screenshot 2023-12-29 094341](https://github.com/Bhagath118/FindMaximum/assets/147473779/7bdf68eb-4f67-4525-86d0-399f571f8acd)

![Screenshot 2023-12-29 094353](https://github.com/Bhagath118/FindMaximum/assets/147473779/8326735e-acb5-4c6f-9603-74e077109dd0)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
