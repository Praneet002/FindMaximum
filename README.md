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
    #Write your code here
    marks.sort()
    large = marks[-1]
    return large
max_marks([10,60,80,30,76,23])


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(list1):
    # write your code here
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1 = i
    return max1
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    # write your code here
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1 = i
    return max1
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![output](https://github.com/Praneet002/FindMaximum/blob/main/Mamimum%20of%20list%20of%20numbers%201.png)
![output](https://github.com/Praneet002/FindMaximum/blob/main/Maximum%20of%20list%20of%20numbers%202.png)
![output](https://github.com/Praneet002/FindMaximum/blob/main/Maximum%20of%20list%20of%20numbers%203.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
