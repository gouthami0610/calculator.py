def calculator(a,b,choice):
    if choice=="+":
        return "The sum of {0} and {1} is {2}".format(a,b,a+b)
    elif choice=="-":
        return "The subtraction of {0) and {1} is {2}".formmat(a,b,a-b)
    elif choice=="*":
       return "The multiplication of {0} and {1} is {2}".format(a,b,a*b)
    elif choice =="/":
        return "The division of {0} and {1} is {2}".format(a,b,a/b)
def display():
    print("Enter two numbers:")
    a=eval(input("Enter first operand :"))
    b=eval(input("Enter second operand :"))
    choice=input("Enter the operator you want to perform :")
    result=calculator(a,b,choice)
    print(result)
while(1):
    ch=input("you want to perform operation then enter y/Y or else enter n/N :")
    if (ch=="y" or ch=="Y"):
        display()
    else:
        break
