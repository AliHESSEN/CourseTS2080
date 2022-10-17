Class diagrams

Describes the type of the objects that can be created
Object = instant of a class
Class diagrams also show the attributes of the classes. Attributes variables and the properties. Any that is bound in a class. That means the parameters of the constructors. Operations of class that can occur. 
Association
Association A and B can call each other. An association is a solid line between two classes, directed from the source class to the target class. The name of the property goes at the target end of the association, together with its multiplicity. 

Type A: 1 =  An order must have precisely one customer))
Type B : 0 = corporate customer may or may not have a single sale rep
Type C : * =  A customer need not place an order, and there is no upper limit ot the number of orders a customer may place – zero or more

Generalization

Inheritance
Is the concept of acquiring the resource from the parents or base class by child class. It allows its properties to be shared is known as the parent class and the class which acquires the properties from its parent class is known as the child class. Inheritance greatly reduces the need to code again and allows code reusability.

Composition
A “has-an” instance of B. B cannot exist without A.

Aggregation
A “has-an” instance of B. B can exist without A.
Aggregation is the same as association


Multiplucity
How man instances of a things a object need from another thing from another object. Feks. How many instances of a pilot at a plane needs
Abstract class
Is a class that cannot be instantiated. An abstract class is designed to be inherited by subclasses that implement or override its methods. You can have functionality in your abstract class -the methods in an abstract class can be both abstract or concrete. 

Uni-association
Mean that A can call B, but B cant not call A.

Interface class
Skrives slik:
<<interface>>
Name
Method1()
Interface classes is just methods. We use interface classes when multiple classes need to use the same method. It helps you crate methods that causes data hiding. It means that some methods will be hidden from some classes. If the methods are hidden, then one can argue that the methods are private or maybe protected. It supports hiding of information and protect client code by publicly declaring certain behaviour
An interface can contain only method declarations.  Interface class must implement all the methods in the class that extends the interface.
A -------------- B
Use Interface: A uses interface B

Abs are either partially implemented or not implemented at all
Interface would need to implement all the methods in the class that extends the interface
Abs allows you to create functionality that subclasses can implement or override.
Interface if you want a contract on some behaviour or functionality. In other words, an interface only allows you to define functionality.
A class can extend only one abstract class, it can take advantage of multiple interface.

Enumerations
Are model elements in class diagrams that represent userdefined data types. It contains set of named identifiers that represent the values of the enumeration.

Data types
<<datatype>>
streetAdress : string
city:string
state:string
zipcode:string
country:string
can be looked at like a struct
Data types are model elements that define data values. You typically use data type to represent primitive types, such as integer or string types, and enumerations, such as user-defined data type.
