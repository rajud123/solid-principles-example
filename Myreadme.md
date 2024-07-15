SOLID Design Principles:
S - Single Responsibility Principle
O - Open & Close principle
L - Liskov Substituion principle
I - Interface Segregation Principle
D - Dependency Inversion principle

Single Responsibility Principle :
    Every class defined must perform a single functionality, implementation of multiple functionalities in a class messes up the code.

Open & Close principle :
    your functionality should be open for new possiblities/extension and closed for modification.
    we can achieve this by creating an interface with the methods, we can have multiple subclass for the interface, achuieve the same functionality 
    in a differnt way or with different inputs, this way with every new subclass we can achieve open for extension.
    The general idea of this principle is great. It tells you to write your code so that you will be able to
    add new functionality without changing the existing code.

Liskov Substitution Princple:
    If class A is a subclass of class B, class A should be a substutte of class B, it means if we replace class B(paernt) with class A(child) 
    there shold be bot be any interruption in logic.
    objects of a superclass shall be replaceable with objects of its subclasses without breaking the application.
    That requires the objects of your subclasses to behave in the same way as the objects of your superclass.
    we can define the behaviours in seaprate interfaces, so the subclasses can extend those interfaces which it realy requires and doesnot reqiued 
    to implment every method in interface whihc it does not suppport

Interface Seggregation Principle:
    This interface states that split the larger interfaces into smaller ones, because the implementation might not need all the methods 
    for implementation. we should not force the client to implement all the methods.
    The goal of Interface seggragation principle is similar to single responsility principle.

Dependency Inversion principle
    Dependency Inversion is the strategy of depending upon interfaces or abstract functions and classes rather than upon concrete functions 

    the dependency inversion principle is a specific methodology for loosely coupled software modules, always code for interfaces never code for
concrete clsases because it increase depndency betwenn client and service, we can have the client with depndency as interface, so there is
no tight coupling of one particular service, we can change the service dynamically at runtime.
