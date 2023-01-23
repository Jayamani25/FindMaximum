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
Developed by: R.Jayamani
RegisterNumber: 22008124
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]
        

```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: R.Jayamani 
RegisterNumber: 22008124
'''
def max_marks(marks):
    return max(marks)


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: R.Jayamani
RegisterNumber: 22008124
'''
def max_marks(list1):
    maxvalue=list1[0]
    for i in range(1,len(list1)):
        if list1[i]>maxvalue:
            maxvalue=list1[i]
    return maxvalue


```
## Sample Input and Output


## Output:
1.![1](https://user-images.githubusercontent.com/85949888/214057277-1ea7aeb0-4f17-4abb-8191-1d248467bc29.png)
2.![2](https://user-images.githubusercontent.com/85949888/214057409-9d04cb46-870f-426c-a515-800fe09bd0a4.png)
3.![3](https://user-images.githubusercontent.com/85949888/214057456-b3a104d0-a50d-4155-a216-d4a737b76171.png)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
