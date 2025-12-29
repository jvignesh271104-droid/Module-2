## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
~~~
num=int(input()) 

rev=0 

temp=num 

while temp>0: 

    rev=(10*rev)+temp%10 

    temp//=10 

    if rev==num: 

        print("The given number {} is a Palindrome".format(num)) 

    else: 

        print("The given number {} is not a palindrome".format(num))
~~~
## Output
<img width="734" height="140" alt="530348381-7e6cda3c-2cce-49ad-a1c5-742a1b41e963" src="https://github.com/user-attachments/assets/8ec106db-2f27-4ea7-ad6e-4deec88e8883" />

## Result
Thus, the program has been successfully executed .
