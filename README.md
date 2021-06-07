import math
print("To find the root of the equation")
print("The general formula is ax^2 + bx + c = 0")
a=int(input("Enter the coefficent of X^2: "))
b=int(input("Enter the coefficent of X: "))
c=int(input("Enter the constant: "))


if b**2>4*a*c :
    print( (-b+ math.sqrt(b**2-4*a*c))/2 )
    print( (-b- math.sqrt(b**2-4*a*c))/2 )
else:
    print("no sloution")
    func=math.sqrt(-b**2+4*a*c)/2
    print((-b)/2,"+","i",func)
    print((-b)/2,"-","i",func)

input("press enter:")
