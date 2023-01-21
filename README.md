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
i)	To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: KAVINRAJA D 
RegisterNumber: 22007928
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
ii)	To find the maximum marks using the list method max().
```
Program to mark the maximum of marks using the list method sort
Developed by: KAVINRAJA D
RegisterNumber: 22007928
def max_marks(marks):
   large = max(marks)
   return large

```
iii) To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by:KAVINRAJA D 
RegisterNumber: 22007928
def max_marks(marks):
    large=max(marks)
    return large
```

## Output:
i)
file:///home/sec/FindMaximum/img/max_marks1.jpg![image](https://user-images.githubusercontent.com/119875375/213873607-b823274f-8fc0-4bb2-bcc6-0586babd3f4d.png)

![Output](./img/sort%20program.png)

ii)
file:///home/sec/Pictures/Screenshots/def%20function.png![image](https://user-images.githubusercontent.com/119875375/213873582-e128bfce-6389-4e6b-89a8-5a108cc8b149.png)

![Output](./img/max.png)

iii)
file:///home/sec/FindMaximum/img/Screenshot%20from%202023-01-14%2009-07-28.png![image](https://user-images.githubusercontent.com/119875375/213873619-e7bb2537-08fd-4a57-925b-35c683e95445.png)

![Output](./img/bullitten%20program.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
