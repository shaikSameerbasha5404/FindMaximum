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
Developed by: shaik sameer basha
RegisterNumber: 22004926
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    return(marks[-1])
```
ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: shaik sameer basha
RegisterNumber: 22004926
'''
def max_marks(marks):
    large=max(marks)
    return large;
    # write your code here
```
iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: shaik sameer basha
RegisterNumber: 22004926
'''
def max_marks(marks):
    #Write your code here
    large=marks[0]
    for i in range(0,len(marks)):
        if marks[i]>=large:
            large=marks[i]
    return large;
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
## Output:
![sortoutput](https://user-images.githubusercontent.com/118707756/213908148-d403e8ea-aeac-4f6d-b6ed-386630b9bd77.png)
![max_output](https://user-images.githubusercontent.com/118707756/213908159-114f5b1a-9ed5-480b-ad3a-55b69182925c.png)
![bulitin_output](https://user-images.githubusercontent.com/118707756/213908196-c8814e0a-798a-4650-96dc-fa96d15cb4d3.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
