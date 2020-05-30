n=int(input("enter the value of 'n' : "))
x=0
y=1
for i in range(n):
    print(x+y)
    x,y=x+y,x
