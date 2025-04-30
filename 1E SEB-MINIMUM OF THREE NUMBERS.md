# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
write a program to find minimum between three float numbers using conditional Expression(Ternary)

## ALGORITHM  
1. Begin the program.  
2. Read the three numbers: `num1`, `num2`, and `num3` from the user.  
3. Compare `num1`, `num2`, and `num3` to find the smallest number:  
   - If `num1` is less than or equal to both `num2` and `num3`, then `num1` is the minimum.  
   - Else, if `num2` is less than or equal to both `num1` and `num3`, then `num2` is the minimum.  
   - Otherwise, `num3` is the minimum.  
4. Print the minimum value along with the input numbers in the format:  
   `"The minimum of num1, num2, num3 is min_num."`  
5. Terminate the program.

## PROGRAM
```python
# Reg.No-212223070004
# Name-dhushanth
# Write your code here
a=float(input())
b=float(input())
c=float(input())
if(a<b)and(a<c):
    print(f"The minimum of {a}, {b}, {c} is {a}")
elif b<a and b<c:
    print(f"The minimum of {a}, {b}, {c} is {b}")
else:
    print(f"The minimum of {a}, {b}, {c} is {c}")
```

## OUTPUT
![image](https://github.com/user-attachments/assets/02c3c915-9b4c-4024-96b8-ca609f711176)


## RESULT
thus the program is executed successfully
