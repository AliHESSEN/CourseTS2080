Lecture 4

Use Case Diagrams:
Use case diagrams shows high level function, and answers what the system does. It shows all the actions that a system or software can have. A system can have multiple software as well. It also helps visualise functions requirements. Functions requirements are requirements that are required for the program to work. F.eks a log in system where you need to insert username and password.
No functional requirement is a requirement that doesn’t effect the whole system or software. It can be colour, height etc. The purpose of a use case is to define a piece of coherent behavior without revealing the internal structure of the subject. Help visualise the functional requirements of a system, including the relationship of “actors” to the essential processes, as well as the relationships among the different use cases.

Use case describe an interaction with actors as a sequence of messages between the system and one or more actors

System boundary:
A system boundary defines the scope and limits of the system. It is shown as a rectangle that spans all use cases of the system. An actor is thing that interacts with the system. A system can also be an actor for another system.

The use cases er egg-formet in a system boundary. The use cases shows the functionality of a system.

Generalization:
It means that one actor can inherit the role of the other actor. The descended one or more use cases that are specific to the role
Associations: A-line between actors and use cases. In complex diagrams, it is important to know which actors are associated with which use cases
Generalization -> 
Include - - -- ->
Extend <- - - - -
Association ___________

•	Include 
relationships represents an invocation of one use case by another use case. From a coding perspective, it is like on function being called by another function

•	Extend 
This relationship signifies that the extended use case will work exactly. The must be meaningful on its own. This means it should be independent and mist not rely on the behaviour of the extending use case.

Login include - ---> (verify password)
Login < ----- extende (show error message)

Include is for “need to” where extend is for “may”
