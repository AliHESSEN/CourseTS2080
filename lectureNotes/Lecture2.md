from abc import ABC

class Animal(ABC):
    def sleep(rest):
        print ("Will rest now")


## making speak functions

def speak(self):
    print ("This function will define the sound by any aniaml")
    
    ## child classes that will inherit from both parent clasees Animal and Speak
    
    class Dog(Animal):
        def speak(self):
            print ("woof, woof")
            d = Dog()
            d.sleep()
            d.speak()
            
    class Cat(Animal):
        def speak(self):
            print ("meow")
            c = Cat()
            c.sleep()
            c.speak()
            
    class Lion (Animal):
        def speak(self):
            print ("ROAR")
            li= Lion()
            li.sleep()
            li.speak()
            
    ## Multiple member

class OldMember:
    def function1(self):
        print ("Hello from old member one")
        
class OldMember2:
    def function2(self):
        print ("Hello from old member two")
        
class OldMember3:
    def function3(self):
        print ("Hello from old member tree ")
        
## multiple inherit

class NewMember(OldMember, OldMember2, OldMember3):
    def function4(self):
        print ("Hello from new member")
        
testing = NewMember()
testing.function1()   
testing.function2()   
testing.function3()
testing.function4()

## Polymorphism

class Shape:
    
    def __init__(self, name):
        self.name = name
        
    def area(self):
        pass
    
    def fact(self):
        return "I am a tow-dimensional shape"
    
    def __str__(self):
        return self.name
    
class Circle(Shape): ##inherit from shape class
    def __init__ (self, radius):
        super ().__init__("circle")
        self.radius = radius
        
    def area(self):
        return pi * self.radius**2
    
shapeCircle = Circle(7)

print (shapeCircle)
print (shapeCircle.area())
print (shapeCircle.fact())
