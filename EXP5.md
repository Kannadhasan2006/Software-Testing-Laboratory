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
Developed by:Kannadhasan J
Register Number: 212224240071
```
def binary_search(arr, x):  
    low = 0  
    high = len(arr) - 1 
    mid = 0  

    while low <= high:  
        mid = (high + low) // 2  
        if arr[mid] < x:  
            low = mid + 1  
        elif arr[mid] > x:  
            high = mid - 1  
        else:  
            return mid
    return -1  

arr = [2, 3, 4, 10, 40]  
x = input("Enter the element to be searched: ")  

try:  
    x = int(x)  
    result = binary_search(arr, x)  
    if result != -1:  
        print("Element is present at index", str(result))  
    else:  
        print("Element is not present in array")  
except:  
    print("Enter a valid input!")
```
### Output:
Output 1:
![Screenshot (89)](https://github.com/user-attachments/assets/e5ff30f1-545b-4208-951f-b3ab9257417b)

Output 2:
![Screenshot (90)](https://github.com/user-attachments/assets/5aca1408-dbef-4754-8282-f7ece22d0dc6)

Output 3:
![Screenshot (91)](https://github.com/user-attachments/assets/aeeb38f6-0b32-436f-bf56-92a2e9dfada0)

Output 4:
![Screenshot (92)](https://github.com/user-attachments/assets/f73c6fc2-ef56-4320-a6de-5d4668384993)

Output 5:
![Screenshot (93)](https://github.com/user-attachments/assets/2b48814a-698e-4eb3-a54a-db13cb375ed2)

Output 6:
![Screenshot (94)](https://github.com/user-attachments/assets/9d3ef0fd-c622-4304-9acf-4ab2e4d56777)

Output 7:
![Screenshot (95)](https://github.com/user-attachments/assets/81722a36-caf8-47e7-add6-43f269375e05)

Output 8:
![Screenshot (96)](https://github.com/user-attachments/assets/1b1d45f4-5d22-480d-88cf-a7f10a4dd3ef)

Output 9:
![Screenshot (97)](https://github.com/user-attachments/assets/435441b3-7caf-4d53-8035-d83d1101ae6f)
### Result:
Thus, the python program to check the number is Armstrong number or not implemented and the output is verified successfully.

