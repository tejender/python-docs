# python-docsentry=True


while entry:
    print("1.add")
    print("2.multiplication")
    print("3.subtraction")
    print("4.division")
    print("Any other key to exit")
    print("Enter your choice :")
    choice = int(input())
    if choice == 1:
        num1 = int(input("enter Fist number :"))
        num2 = int(input("enter second number :"))
        num3=num1 + num2
        print("sum=",num3)
    elif choice==2:
        num1 = int(input("enter Fist number :"))
        num2 = int(input("enter second number :"))
        num3 = num1 * num2
        print("multiplication",num3)
    elif choice==3:
        num3 = num1 - num2
        print("subtraction",num3)
    elif choice==4:
        num1 = int(input("enter Fist number :"))
        num2 = int(input("enter second number :"))
        num3 = num1 / num2
        print("division",num3)
    else:
        print("exiting ")
        entry=False
        break

    print("want to perform another operation y/n")
    entry= input()
    if entry.lower()=='y':
        entry='y'
    else:
        entry=False
print("exit")
