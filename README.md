--Python  Decorator

--a decorator takes in a function, adds some functionality and returns it.

def decorateit(func):
    def inner():
        print("I got decorated")
        func()
    return inner

def Undecorated():
    print("I am yet to be decorated")
    
-- Python Class creating a class
class Class1():
    def __init__(self,attribute1,attribute2):
        self.attribute1=attribute1
        self.attribute2=attribute2
        --hidden attributes
        self.attribute3= 50
        self.attribute4=0
        print(attribute1+attribute2)
    def method1(self):
    self.attribute4=self.attribute3
 -- Creating an object from a class
 object1=Class1('firstattribute','secondattribute')
 -- accessing attibute values
 print(object1.attribute1)
 print(object2.attribute2)
 
        
