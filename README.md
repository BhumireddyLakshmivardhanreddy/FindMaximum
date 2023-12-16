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
Program to mark the maximum of marks using the list method sort
Developed by: B.LAKSHMI VARDHAN REDDY
RegisterNumber: 23009662

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by:B.LAKSHMI VARDHAN REDDY 
RegisterNumber: 23009662
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: B.LAKSHMI VARDHAN REDDY
RegisterNumber: 23009662
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![sort](https://github.com/BhumireddyLakshmivardhanreddy/FindMaximum/assets/148514637/f37df549-fd76-4000-96cc-fc0f0bba7eba)
![max()](https://github.com/BhumireddyLakshmivardhanreddy/FindMaximum/assets/148514637/e07f79ae-c60e-48ab-ad1e-3da545cd078b)
![builtin](https://github.com/BhumireddyLakshmivardhanreddy/FindMaximum/assets/148514637/a282b488-a2f0-4415-8f73-7d67db45e2f4)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
