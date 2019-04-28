--Python  Decorator

--a decorator takes in a function, adds some functionality and returns it.

def decorateit(func):
    def inner():
        print("I got decorated")
        func()
    return inner

def Undecorated():
    print("I am yet to be decorated")
    
