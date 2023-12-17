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
#Program to mark the maximum of marks using the list method sort
#Developed by: VENKATANATHAN P R
#RegisterNumber: 23000285
def max_marks(marks):
    marks.sort(reverse=True)
    return marks[0]

```

ii)	# To find the maximum marks using the list method max().
```
#Program to find the maximum marks using the list method max().
#Developed by: VENKATANATHAN P R
#RegisterNumber: 23000285
def max_marks(marks):
    return max(marks)

```

iii) # To find the maximum marks without using builtin functions.
```
#Program to the maximum marks without using builtin functions.
#Developed by: VENKATANATHAN P R 
#RegisterNumber: 23000285
def max_marks(list1):
    largest=list1[0]
    for i in range(1,len(list1)):
        if(list1[i]>largest):
            largest=list1[i]
    return largest

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![image](https://github.com/23000285/FindMaximum/assets/138970859/eee7d050-950f-4b5c-85b2-5231984086d8)

![image](https://github.com/23000285/FindMaximum/assets/138970859/c3882c36-60ec-4ff8-84d2-410cd9d85166)


![image](https://github.com/23000285/FindMaximum/assets/138970859/ee79b197-5ab0-41a5-922e-fe816edb686b)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
