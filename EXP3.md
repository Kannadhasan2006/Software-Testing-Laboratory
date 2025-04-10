# Ex.No: 3 To check the number is prime or not and inspect for failures.
 
### DATE:    10/04/2025                                                                        
### REGISTER NUMBER : 212224240071
### AIM: 
Write a python program to check the number is prime or not and inspect for failures.
 
### Algorithm:
1. Start the program.
2. Get the number to be checked from the user.
3. If the number is less than or equal to 1, return "Not Prime".
4. If the number is 2, return "Prime".
5. Start the iteration from 3, For each iteration:
6. If the number is divisible by the current iteration value, return "Not Prime".
7. If the number is not divisible by any value from 2 to the square root, return "Prime".
8. Stop the program.

### Program:
```
num = input("enter:")
flag = 0
if num.isnumeric():
    z = int(num)
    if (z == 2):
        flag = 1
    if (z > 2):
        for i in range(2, z // 2):
            if z % i == 0:
                flag = 0
                break
            else:
                flag = 1
    if (flag == 1):
        print("Prime Number")
    else:
        print("Not a Prime Number")
else:
    print("Enter a Positive Number")

```
### Output:
case:1
![Screenshot 2025-04-10 082150](https://github.com/user-attachments/assets/9f6bb9d6-1ffd-4f18-9b04-ed6dff09eaa4)

case:2
![Screenshot 2025-04-10 082240](https://github.com/user-attachments/assets/751fc83d-4c3d-459a-a712-dc022e3edfc6)

case:3
![Screenshot 2025-04-10 082308](https://github.com/user-attachments/assets/662358b3-cbe6-4894-ab2a-8b55f34cd8e8)

case:4
![Screenshot 2025-04-10 082324](https://github.com/user-attachments/assets/8be919dd-78b3-43af-a41a-0dc7787ea0b8)

case:5
![Screenshot 2025-04-10 082347](https://github.com/user-attachments/assets/ba7533a3-b0dc-4c71-ba80-58c810e483eb)

case:6
![Screenshot 2025-04-10 082527](https://github.com/user-attachments/assets/5900aee6-16d4-4d42-9a92-de7efab83c3a)

case:7
![Screenshot 2025-04-10 082546](https://github.com/user-attachments/assets/95bfe851-aa33-4f78-8b42-e3d4441aaaa4)

case:8
![Screenshot 2025-04-10 082606](https://github.com/user-attachments/assets/cfca76ce-8164-4c7b-826a-1d80a2c7439a)

case:9
![Screenshot 2025-04-10 082634](https://github.com/user-attachments/assets/a3889833-6393-4a9e-99bb-f0f6cc9656fd)


### Result:
Thus, the python program to check the number is prime or not is implemented and the output is verified successfully.
