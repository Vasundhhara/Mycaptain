# Mycaptain
Assignments for Mycaptain

I'm here to help Isha get a Mycaptian's Artificial Intelligence certificate

First Assignment(Fibonacci series)

def fib(n):
    a=0
    b=1

    if n==1:
        print(a)
    elif n<0:
            print("not defined")

    else:
        print(a)
        print(b)

        for i in range(2,n):
            c=a+b
            a=b
            b=c
            print(c)

fib(5)
