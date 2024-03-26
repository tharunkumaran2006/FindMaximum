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

i) To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```



## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/tharunkumaran2006/FindMaximum/assets/151625188/4f1857f9-0cc7-4fa8-8ca3-65044e34521b)

ii)	# To find the maximum marks using the list method max().
![image](https://github.com/tharunkumaran2006/FindMaximum/assets/151625188/75177866-4fc8-4fa7-8a74-c5260340466e)

iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/tharunkumaran2006/FindMaximum/assets/151625188/6dcbf8f0-22c1-4d2e-b94f-3d4bd7109534)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
