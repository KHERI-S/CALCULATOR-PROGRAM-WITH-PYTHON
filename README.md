# CALCULATOR-PROGRAM-WITH-PYTHON


def add(x, y):
    return x + y

def substract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def division(x, y):
    return x / y
print("Welcome To Calculator")
print()  
while True:
    print ("Select Operation: \n (1) Addition \n (2) Subtraction \n (3) Multiplication \n (4) Division")

    operation =input ("Enter Your Choice (1/2/3/4):")
    num1 =float(input("Enter Your First Number: "))
    num2 =float(input("Enter Your Second Number: "))

    if operation == '1' :
        print("Output is : ", add(num1, num2))
    elif operation == '2' :
        print("Output is : ", substract(num1, num2))    
    elif operation == '3' :
        print("Output is : ", multiply(num1, num2))   
    elif operation == '4' :
        print("Output is : ", division(num1, num2))    
    else :
        print("Invalid Operation")     
