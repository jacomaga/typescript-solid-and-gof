## Solid

### SRP - Single Responsibility Principle

A class needs to have only one responsibility and objective.

The benefit of this is having a better organization of responsibilities and functionalities. It also improves the maintainability of your projects because if you need to make changes, they will be highly isolated within the specific class. This means that modifying one class won't require changes in other classes.

Additionally, if you want to add more methods, having isolated classes allows you to add them to the specific class without impacting other parts of the code.


### OCP - Open/Closed Principle 

Classes, funcitons, etc.  should be open for extension, but closed for modification. In essence, the behavior of a system can be extended without modifying its source code. This principle aids in maintaining the stability, robustness, and reusability of a software system, minimizing the risk of introducing new bugs when implementing changes.


### LSP - Liskov Substitution Principle

If a program is using a base class, it should be able to use any of its subclasses without the program knowing it. In other words, the subclasses must be substitutable for their base class without affecting the correctness of the program. LSP is intended to enforce strong behavioral subtyping and ensures semantic interoperability of types in a hierarchy, which leads to a more robust and reliable software system.

### ISP - Interface Segregation Principle

Clients should not be forced to depend on interfaces they do not use. This means that a class should not have to implement methods it doesn't use. Instead of one large, bulky interface, it's better to have several smaller, more specific interfaces. In other words, it's better to have many specific interfaces than one general-purpose interface. By following ISP, we can achieve a system that is more maintainable, flexible, and organized.