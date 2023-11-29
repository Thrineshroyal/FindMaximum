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
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    l=max(marks)
    return l


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
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![image](https://github.com/Thrineshroyal/FindMaximum/assets/145741928/8b5c4076-12ad-4f8e-ad24-114766c7c1fb)

![image](https://github.com/Thrineshroyal/FindMaximum/assets/145741928/974f6015-6df2-45b3-8e78-6bb0341782fc)

![image](https://github.com/Thrineshroyal/FindMaximum/assets/145741928/12e933a6-ea52-4331-9c2e-09cd0e2b040e)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
