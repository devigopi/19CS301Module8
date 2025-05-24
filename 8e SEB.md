EX:Return the Resulting string
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

Program:
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

![8E](https://github.com/user-attachments/assets/c189e1bb-e868-4983-a2c8-4ca11863554c)

Result:
Thus, the given program is implemented and executed successfully .

