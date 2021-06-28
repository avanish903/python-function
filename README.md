# python-function
this is code for function 
def function1():
    """this is the function foe adding two number"""
    
    print("hello you are infunction 1 please enter the first number")
    v1=int(input())
    print("enter the second number")
    v2=int(input())
    sum=v1+v2
    print(sum)
    return sum
    
v=function1()
print(v)
print(function1.__doc__)
    
