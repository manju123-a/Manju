num1=int(input())
num2=int(input())
print("sum:",num1+num2)

#area of circle
r=int(input())
pi=3.14
circle=pi*(r**2)
print("area of the circle:",circle,sep="")
print(f"area of the circle:{circle}")

#qudratic equation
a=int(input("give a:"))
b=int(input("give b:"))
c=int(input("give c:"))
root1 =0
root2 = 0
d=(b**2)-4*a*c
root1=(-b+ (d**(0.5)))/2*a
root2=(-b -(d**(0.5)))/2*a

print(f"Roots:({root1},{root2})")

#converting into temperture
#f=c*(9/5)+32
#k=273+c
c=int(input("tempertaure_celsius="))
f=c*(9/5)+32
k=273+c
print("temperature in fahrenheit:",f)
print("temperature in kelvin:",k)

#basic currency convertor
#1usd=0.85
#100usd=eur*100
a=int(input("amount_in_usd="))
b=float(input("exchange_rate_usd_to_eur="))
c=a*b
print("Equivalent amount in EUR:",c)

#average of 3 nums
'''num1=int(input("enter first number:"))
num2=int(input("enter the second number:") )
num3=int(input("enter the  third number:") )
average=(num1 +num2 +num3)/3
print("The average of the three numbers is", average)

#adding strings
a=input("enter the first name:")
b=input("enter the last name:")
c=a+""+b
print("your full name:",c)

#repeating string
m=input("Enter a word:")
n=int(input("How many times do you want to repeat it?"))
p=m*n
print(p)

perimeter of a rectangle
l=int(input("Enter the length of the rectangle:"))
w=int(input("Enter the width of the rectangle:"))
p=2*(l+w)
print("The perimetr of the rectangle is:",p)

#finding suare and cube
a=int(input("Enter a number:"))
square=a*a 
cube=a*a*a 
print("square of the number:",square)
print("cube of the number:",cube)

#find the remainder and quo
a=int(input("Enter the dividened:"))
b=int(input("Enter the divisior:"))
q=a/b
r=a%b 
print("quotient:",q)
print("remainder:",r)


