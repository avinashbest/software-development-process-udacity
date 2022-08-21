# Software Engineering and UML:

## Object Orientation Introduction:

- Precedence of data over functions.
- Information hiding (Encapsulation & Segregation of data behind well-defined & ideally stable interfaces).
- Encapsulation technique to achieve the information hiding.
- It allows to reuse of object definitions (Inheritance & Polymorphism).

## Objects and Classes:

- An `object` is an computing unit organized around a collection of state or instance variables that define the state of the object. In addition, each object has associated with it a set operations or methods that operate on such state. The operations & methods read/write instance variables. (i.e, state variables or attributes & operations or methods).

- A `class` is basically a template. A blueprint, from which new objects, which is instances of the class can be created.

## Benefits of Object Orientation:

- Reduce maintenance costs.
- Improve development process.
- Enforce good design principles.

**Q. Acme corporation decided to use an object oriented approach in its software development process. What benefits can they expect to receive from this decision?**

    [✅] increased reuse because of the modular coding style
    [✅] increased maintainability because the system design can accommodate changes more easily.
    [❌] increased speed because object oriented systems tends to run faster.
    [✅] increased understandability because the design models real-world entities.

## OOAD: Object Orientated Analysis & Design:

OOAD is a software engineering approach whose main characteristics is to model a software system as a group of interating objects.

Object Oriented Analysis, which is a requirements analysis technique that concentrates on modeling real world objects.

`History`: `James Rumbaugh`, which in the 90s developed an integrated approach to object oriented modelling with three main aspects.

- A `data aspects`, so the modelling was based on using an extended version of entity relationship diagrams to describes classes & inheritance. So that's what was called `object-model`.

- Second aspects, has to do with functions. So data flow diagrams were used to represent the `functional aspects` of the system, where each function was then becoming a method in a class. So this is called the `functional model`.

- The third model has to do with `control`. So it was representing the `dynamic aspects `of a system. And it uses state machines to represent how a system would evolve going from one state to the other based on what happened to the system.

These three model together called as `Object Modeling Technique (OMT)`.

> NOTE: Object Modeling Technique (OMT) + Jacobson and Booch, evolved into Unified Modeling Language (UML).

> UML extends OMT by providing more diagrams and a broader view of system from multiple perspectives.

## Analysis Overview:

- Functional Oriented View -> Data Oriented View
- Real world objects -> Requirements:

        1. Obtains/prepare textual description of problem.
        2. Underline nouns -> Classes.
        3. Underline adjectives -> Attributes of the classes.
        4. Underline active verbs -> Operations on the classes.

**Q. Consider the following requirements for an online shopping website: "Users can add more than one item on sale at a time to a shopping cart". Which of the following elements should be modeled as classes?**

    [✅] item
    [❌] sale
    [✅] shopping cart
    [❌] time
    [✅] user

## Running Example: Course Management System

- The registration manager sets up the curriculum for a semester using a scheduling algorithm.
- One course may have multiple course offerings.
- Each course offering has a number, location and time.
- Students selet 4 primary courses and 2 alternative courses by submitting a registration form.
- Students may use the system to add/drop courses for a period of time after registration.
- Professors use the system to receive their course offering rosters.
- Users of the registraitons system are assigned passwords which are used at login validation.

## UML Structural Diagrams: Class Diagram

- These are the diagrams that represents static characteristics of the system that we need to model. This is in contrast with dynamic models which instead behaviours of the system that we need to model. 

- A `Class Diagram` represents a `static`, `structural view of the system`, and it describes the classes and their structure, and the relationships among classes in the system. 

## Class Diagram: Class

