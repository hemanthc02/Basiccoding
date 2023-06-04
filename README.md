# Basiccoding
//Odd or Even using Python//
a=int(input("enter the number"))
if a==0:
    print("the given number is not a odd nor a even")
elif a<0:
    print("these are the  negative numbers")
elif a%2==0:
    print("the given number is even")
else:
    print("the given number is odd")

ODD OR EVEN CODE USING PYTHON

//multiline string using list and while loop
para=[]
print("enter the para:")
while True:
    line=input()
    if line:
        para.append(line)
    else:
        break
print(para)


//Guess

i=1
while True:
    if i%3==0:
        break
    print(i) 
    i+=1

//Fibonacci series
n=int(input("enter the value:"))
f=0
s=1
for i in range(n):
    print(f)
    temp=f
    f=s
    s=temp+s

//Factorial in python

n=int(input("enter the number:"))
fac=1
if n<0:
    print("negative value has no factorial")
elif n==0:
    print("the factorial of 0 is 1")
for i in range(1,n+1):
    fac=fac*i
    print(fac)

//Star=for loop execution
for i in range(9):
    for j in range (i):
        print("!",end=" ")
    print(" ")
    


