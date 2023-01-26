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
Developed by:  NATHIN R
RegisterNumber:  22008510
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: NATHIN R
RegisterNumber: 22008510
'''
def max_marks(marks):
    large=max(marks)
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: NATHIN R
RegisterNumber: 22008510
'''
def max_marks(list1):
    max=list1[0]
    for number in list1:
        if(number > max):
            max = number
    return max



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![image](https://user-images.githubusercontent.com/118679646/214790721-7b2c8647-9215-47bc-9be3-40a9f2630f30.png)

![image](https://user-images.githubusercontent.com/118679646/214791269-0f304c46-3de8-43f7-874e-3124222354a8.png)

![image](https://user-images.githubusercontent.com/118679646/214791401-d80ed15f-20e8-4386-bfe3-a30f01b54797.png)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
