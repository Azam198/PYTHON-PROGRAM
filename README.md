# PYTHON-PROGRAM
no=int(input("Enter any no"))
temp=0
while no>0:
        rev=no%10
        no=no//10
        temp=temp*10+rev
        print("Reverse is:",temp);
