# 19CS301Module8
EXPTNO.8a Program to find Find the simple interest

### Aim: Find the simple interest by getting the principal, rate and time value from the user

STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create variable 'p','r','t' for principal,rate of interest and time. STEP 4: Get the input of p,r and t from user.

STEP 5 : Using the formula (p*r*t)/100 calculate the result. STEP 6: Print the result.

STEP 7: Stop.

### Program:
```
def simpleInterest(p,t,r):
      si = p*t*r/100
       return si
p = eval(input())
r = eval(input())
t = eval(input())
```
### Output:
![image](https://github.com/user-attachments/assets/0cc71222-9697-4545-a937-b330407cbc02)





### Result: Thus, the given program is implemented and executed successfully .

EXPTNo.8b The included code stub will read an integer, , from STDIN.
Without using any string methods, try to print the following:123...n
Note that "..." represents the consecutive values in between.

### Aim:The included code stub will read an integer, , from STDIN.
Without using any string methods, try to print the following:123...n
Note that "..." represents the consecutive values in between.
### Algorithm:
Step 1: Start
Step 2: Read the integer n from user input
Step 3: Define a recursive function print_numbers(n)
  Step 3.1: If n == 0, return (base case)
  Step 3.2: Recursively call print_numbers(n - 1)
  Step 3.3: Print the value of n (without newline)
Step 4: In the main part of the program, call print_numbers(n)
Step 5: End

### Program:
```
n = int(input())
for i in range(1,n+1):
    print(i,end="")
```
### Output:

![8a](https://github.com/user-attachments/assets/d22dbd0b-aea5-4a0a-86ab-8675dbb31580)

### Result: Thus, the given program is implemented and executed successfully .
 

EXPT NO>8C To Write a python program to Given the participants'	score sheet for your University Sports Day, you are required to find the runner-up score
### Aim: To Write a python program to Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given scores. Store them in a list and find the score of the runner-up.


### Algorithm:
STEP 1: Start.

STEP 2: Create a variable n.

STEP 3: Get the value of n from user.

STEP 4: Get the number of inputs from user and split the input and append in a list. STEP 5: Using set function remove duplicates from the list.

STEP 6: Using sort function reorder the list in ascending order. STEP 7: Print the result.

STEP 8: Stop.


### Program:
```
n = int(input())
arr = list(map(int, input().split()))
arr.sort()
large=arr[-1]
arr.reverse()
for i in range(len(arr)-1):
    if arr[i+1]<arr[i]:
        print(arr[i+1])
        break
```

### Output:

![8d](https://github.com/user-attachments/assets/7de9ef21-a11e-4bbc-8495-36bcbe11c3fa)


 

### Result: Thus, the given program is implemented and executed successfully .
 


EX: 8.d program to square all the even numbers and cube all odd numbers from a list of integers
### Aim: To Develop a python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list.


### Algorithm:

STEP 1: Start.

STEP 2: Create a variable f and l for upper and lower limit of list. STEP 3: Get the value of f and l from user.

STEP 4: Create a list.

STEP 5 : Get the input from user and append in the list. STEP 6: Create a lambda function to calculate the result. STEP 7: Print the result.

STEP 8 : Stop.

### Program:
```
cube = lambda x: x**2 if x%2==0 else x**3
def fun(f,l):
    l1=[]
    for i in range(f,l+1):
        l1.append(i)
    return l1
f,l = int(input()),int(input())

```
### Output:

![8f](https://github.com/user-attachments/assets/f6ffae43-0edd-453a-851b-88ea00ca46cd)




### Result: Thus, the given program is implemented and executed successfully .

8E EX:Return the resulting string.

Aim: Write a Python program to find the first appearance of the substring 'not' and 'poor' from a given string, if 'not' follows the 'poor', replace the whole 'not'...'poor' substring with 'good'. Return the resulting string.

Algorithm:
Step 1:Start
Step 2:Input a string from the user.
Step 3:Find the index of the first occurrence of the substring 'not'.
Step 4:Find the index of the first occurrence of the substring 'poor'.
Step 5:If both substrings are found, and 'poor' comes after 'not':
  Replace the substring from 'not' to the end of 'poor' with 'good'.
Step 6:Return the updated string.
Step 7:End

program:
```
def not_poor(str1):
    snot =str1.find('not')
    spoor =str1.find('poor')
    if spoor>snot and snot>0 and spoor>0:
        str1 = str1.replace(str1[snot:(spoor+4)],'good')
        return str1
    else:
        return str1
print(not_poor("The lyrics is not that poor!"))
```
Output:

![8E](https://github.com/user-attachments/assets/44b29176-3511-4cb2-a16c-11c5b1eee281)

Result:
     Thus, the given program is implemented and executed successfully .
 


