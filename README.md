#calucator in python

x = float (input ("enter the first number: "))
y = float (input ("enter the second number: "))
op = input ("enter the operator: ")

if op == "+":
   add = x+y
   print (add)
elif op == "-":
   sub = x-y
   print (sub)
elif op == "*":
   mul = x*y
   print(mul)
elif op == "/":
   div = x/y
   print (div)
else:
   print ("invalid operator")
