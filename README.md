# UML
The Unified Modeling Language(UML) is a notation that you can use for object-oriented analysis and desgin.
</br>
### Class Diagram
A class diagram is a diagram that shows classes, interfaces, and their relationships.
In the design of a system, a number of classes are identified and grouped together in a class diagram that helps to determine the static relations between them. With detailed modelling, the classes of the conceptual design are often split into a number of subclasses.
#### Structure
</br>The most basic element of a class diagram is a class
</br>Classes are drawn as rectangles. 
</br>The rectangles can be divide into two or three compartments. 
* The top compartment contains the name of the class. 
* The middle compartment lists the class's variables. 
* The bottom compartment lists the class's methods.

**The variables in the middle compartment are indicated as:**   
</br>**visibilityIndicator name : type**
**An initial value can be indicated for a variable by following the variable's type with an equal(=)sign:**
</br>**Shutdown : boolean = false **

</br>**The methods in the bottom compartment are indicated as: **
</br>**VisibilityIndicator name | formalParameters | :return type**

#### Visibility indicators
</br>The symbols that precede each variable and method are visibility indicators.
</br>There are three different types of **visibility indicators**.
* private(-)
* public(+)
* protected(#)
* Derived(can be combined with one of the others)(/)
* Package(~)
* Random(*)
#### Scope
The UML specifies two types of scope for members: **instance and classifier**, and the latter is represented by underlined names.
**If a variable is underlined that means that it is a static variable.**
</br>**This applies to methods, too. Underlined methods are static methods.**


