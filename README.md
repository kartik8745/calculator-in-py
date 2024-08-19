# calculator-in-py
a=int(input("enter value of a:  "))
b=int(input("enter value of b:  "))
op=input("""enter operater 
         give + for addition 
         give - for subraction 
         give * for multiplication 
         give / for divide 
         give % for modulus:  """)  

if(op=="+"):
    print("your addition is:  ",a+b)
elif(op=="-"):
    print("your subtraction is:  ",a-b)
elif(op=="*"):
    print("your multiplication is:  ",a*b)
elif(op=="/"):
    print("your divide is:  ",a/b)
elif(op=="%"):
    print(" modulus of this is:  ",a%b)
else:
    print('enter correct operator:  ')
    
print("thanku for using kartik's calculator ")    
