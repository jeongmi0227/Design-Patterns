# SOLID

## Single Responsibility Principle
There should never be more than one reason for a class to change.
The class provides a very focused functionality or it addresses a specific concern of our desired functionality

## Open-Closed Principle
Software entities(Classes, Modules, Methods etc.) should be open for extenstion, but closed for modification.
Open for Extension: extend existing behavior 
Closed for Modification: Existing code remains unchanged

Derived class can override a method (Open for extension - can derive from base & override methods)
Should not modify the code that is written in a base class(Closed for Modification - avoid modifying base class) 
Avoid modifiying existing base classes and using inheritance and overriding in order to achieve extension of existing behavior.
