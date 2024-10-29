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
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max

```



## Output:
![image](https://github.com/user-attachments/assets/b73e1ea1-26c6-4a0c-b82b-6aab3d7dd02c)
![image](https://github.com/user-attachments/assets/0a54c6fe-7574-4f44-8c35-9b3cad84efb8)
![image](https://github.com/user-attachments/assets/1b674894-f8fb-44fa-9e07-fe1b57fcd65b)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
