# Faulty-Calulator
This Calculator is a faulty calculator 

Var1=int(input("Enter number 1: "))
Var2=int(input("Enter number 2: "))
print("What You Want to Do? "+'+','-','/','*')
Var3=input()

if Var1==45 and Var2==3 and Var3=='*':
    print(555)

elif Var1==56 and Var2==9 and Var3=='+':
    print(77)

elif Var1==56 and Var2==6 and Var3=='/':
    print(4)

elif Var1==85 and Var2==8 and Var3=='-':
    print(225)

elif Var3=='+':
    plus=Var1+Var2
    print(plus)


elif Var3=='*':
    Multiply=Var1*Var2
    print(Multiply)


elif Var3=='/':
    Divide=Var2/Var1
    print(Divide)


elif Var3=='-':
    Sub=Var2-Var1
    print(Sub)

else:
    print("Out of Range")

