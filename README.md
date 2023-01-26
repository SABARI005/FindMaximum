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
```
i) # To find the maximum of marks using the list method sort.

Developed by: SABARI S
RegisterNumber: 22008698
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
ii) # To find the maximum marks using the list method max().

Developed by: SABARI S
RegisterNumber:22008698
def max_marks(marks):
    large=max(marks)
    return large
iii) # To find the maximum marks without using builtin functions.

Developed by:SABARI S
RegisterNumber: 22008698
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![WhatsApp Image 2023-01-26 at 13 10 39](https://user-images.githubusercontent.com/118660461/214781995-676f890c-aff3-4da5-97b2-28ed292e48b1.jpg)
![WhatsApp Image 2023-01-26 at 13 10 39](https://user-images.githubusercontent.com/118660461/214782015-0ae639d2-e79f-4583-ab45-91611533c16f.jpg)
![WhatsApp Image 2023-01-26 at 13 10 39](https://user-images.githubusercontent.com/118660461/214782041-23f5dd32-75bf-49b7-bf28-de56026f9de4.jpg)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
