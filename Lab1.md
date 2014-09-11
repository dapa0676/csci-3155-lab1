# Lab 1

1a)

Line 4: pi bound at line 3

line 7: pi bound at line 1

At line 3, pi is rebound for f()

1b)

x in line 3 bound at line 2

x in line 6 bound in line 5

x in line 10 bound in line 5

x in line 13 bound in line 1

X is bound in line 1,2,5, and 8 for different scopes. The above values represent the effective scope of each.

2)

a:int=1, b:(int,int) = (x,3)

If (x==0): (b,1) = ((int,int),int)

else:	(b, a+1) = ((int,int),int)

Def g(x:int): ((int,int),int) because

>(b,1): ((int,int),int) because

>>b: (int,int)

>>1: int

>(b, a+1): ((int,int),int because

>>b: (int,int)

>>a+1: int because

>>>a: int

>>>1: int