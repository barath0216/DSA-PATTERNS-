PATTERN 1

***
***
***
***

def func():
    n=int(input("enter the number"))
    for i in range(0,n):
        for j in range(0,n):
            print("*",end="")
        print("")
func()

PATTERN 2

*
**
***
****

def func():
    n=int(input("enter the number"))
    for i in range(0,n):
        for j in range(0,i+1):
            print("*",end="")
        print("")
func()

PATTERN 3

****
***
**
*

def func():
    n=int(input("enter the number"))
    for i in range(n,0,-1):
        for j in range(0,i):
            print("*",end="")
        print("")
func()

PATTERN 4

*
***
*****
*******

def func():
    k=0
    n=int(input("enter the number"))
    for i in range(0,n):
        for j in range(0,k+1):
            print("*",end="")
        k=k+2
        print("")
func()

PATTERN 5

1
23
345
4567

def func():
    k=1
    n=int(input("enter the number"))
    for i in range(1,n+1):
        for j in range(i,i+k):
            print(j,end="")
        k=k+1
        print("")
func()

PATTERN 6
1
12
123
1234

def func():
    n=int(input("enter the number"))
    for i in range(1,n+1):
        for j in range(1,i+1):
            print(j,end="")
        print()
func()


PATTERN 7

A
AB
ABC
ABCD
def func():
    n=int(input("enter the number"))
    for i in range (0,n):
        k=ord("A")
        for j in range (0,i+1):
            print(chr(k),end="")
            k=k+1
        print()
func()

PATTERN 8
A
BC
DEF
GHIJ
def func():
    n=int(input("enter the number"))
    k=ord("A")
    for i in range (0,n):
        for j in range (0,i+1):
            print(chr(k),end="")
            k=k+1
        print()
func()
