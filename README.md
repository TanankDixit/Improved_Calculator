# Improved_Calculator
I have learned more about python, i have made another calculator but this one works by taking input operators (last one use to do all arithmetic at once)
# code
     import sys
print("hello user")
try:
    first_number= int((input("enter your 1st number")))
    second_number= int((input("enter your 2nd number")))
except ValueError:
    print("invalid numeric values")
    sys.exit()
    #the user will now enter the operator such as +,- etc.
    
operator= input("enter your operator +,-,/,*")
if operator == '+':
    print(first_number+ second_number)
elif operator == '-':
    print(first_number-second_number)
elif operator == '/':
    print(first_number/second_number)
elif operator == '*':
    print(first_number*second_number)
else:   
    print("invalid operator")

print("thank you for using")
