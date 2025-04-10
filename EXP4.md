# Ex.No: 4 check the given number is Armstrong number or not and inspect for failures.
### DATE: 10/04/2025                                                                           
### REGISTER NUMBER : 212224240071
### AIM: 
Write a python program to check the number is Armstrong number or not and inspect for failures.

### Algorithm:
1.  Start the program.
2.	Read an integer input number.
3.	Initialize the variables current_digit, sum = 0, and num = number.
4.	Repeat Steps 5 to 7 until num > 0
5.	current_digit = (num % 10).
6.	sum = sum + (current_digit * current_digit * current_digit). 7. Stop the program.
7.	num = num / 10.
8.	Check if sum == number. If true, print "It is an Armstrong Number." Otherwise, print "It is not an Armstrong Number."
9.	Stop the program.

### Program:
```
a = input("Enter: ")
b = len(a) 
if a.isdigit(): 
    a = int(a)
    

    t = a
    s = 0
    while t > 0:
        d = t % 10
        s = s + (d ** b)
        t //= 10

    if a == s:
        print("Armstrong number")
    else:
        print("Not an Armstrong number,enter positive or numeric number value")
print("enter a digit or positive number")

```
### Output:
case:1
![Screenshot 2025-04-10 085800](https://github.com/user-attachments/assets/b480ab28-9026-441f-90b5-eb8ef02b9ec9)
case:2
![Screenshot 2025-04-10 085813](https://github.com/user-attachments/assets/1d70d5ef-33db-4095-a60e-221b9acd9ee7)
case:3
![Screenshot 2025-04-10 085837](https://github.com/user-attachments/assets/afa06e03-cecf-41fa-b072-1aa8eb7388a2)
case:4
![Screenshot 2025-04-10 085931](https://github.com/user-attachments/assets/abc4dc84-32c9-4e4e-a3c5-26bf80512f3f)
case:5
![Screenshot 2025-04-10 090000](https://github.com/user-attachments/assets/2a98e9ff-4eb8-4bba-9807-e15b21d344bd)
case:6
![Screenshot 2025-04-10 090022](https://github.com/user-attachments/assets/5ea48b7a-fcf0-4ac6-8546-cebc5f8f3ab2)
case:7
![Screenshot 2025-04-10 090039](https://github.com/user-attachments/assets/e671ee3a-4481-4331-b8b1-95a170f5fd4d)
case:8

![Screenshot 2025-04-10 090100](https://github.com/user-attachments/assets/1a1dde5d-0f6f-45f0-b59e-3d3ef39602c5)

case:9
![Screenshot 2025-04-10 090117](https://github.com/user-attachments/assets/a93aa64f-fdcd-4840-8f51-2bc736492c62)



### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.


