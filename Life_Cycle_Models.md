# Life Cycle Models

## Introduction with Barry Boehm

![image](res/12.png)

The bottom line is that choosing the right lifecycle model is fundamental importance.

## Traditional Software Phases

Software engineering is an important and critical discipline, concerned with cost effective software development. This is based on a systematic approach that uses appropriate tools and techniques, operates under specific development constraints. And most importantly, follows a process.

![image](res/13.png)

## Requirements Engineering

It is a field within software engineering that deals with establishing the needs of stakeholders that are to be solved by software.

**Why is this phase so important?**

In general, the cost of correcting an error depends on the number of subsequent decisions that are based on it. Therefore, errors made in understanding requirements have the potential for greatest cost because many other design decisions depends on them and many other follow up decisions depend on them.

![image](res/14.png)

If we discover a problem in `maintenance` we're left to undo a lot of decision that we had made before to correct the error. Whereas if we find an error in `requirements` we can correct it right away and we don't affect the subsequent phases.

**How can we collect the right requirements?**

Traditional requirements engineering does so through a set of steps:

- `Elicitation` which is the collection of requirements from stake holders and other sources and can be done in a variety of ways.

- `Requirement Analysis` which involved the study and deeper understanding of the collective requirements.

- `Specification` of requirements, in which the collective requirements are suitably represented, organized and save so that they can be shared.

- `Validation` to make sure they're complete, consistent, no redundant and so on. So that they've satisfied a set of importance properties, for requirements.

- `Requirements Managements` which accounts for changes to requirements during the lifecycle of the project. And here

## Design

`Software Design` is the phase where software requirements are analyzed in order to produce a description of the internal structure and organization of the system.

Traditionally, the software design phase consists of a series of design activities. Which normally consists of the `architectural design phase`, `the abstract specification` , `interface design`, `component design`, `data structure` and `algorithm design`.

The important point is that we go from sort of `a high-level view of the system`, which is the architectural design, `to a low-level view`, which is the algorithm design. And these activities result in a set of design products, which describe various characteristics of the systems.

**For e.g,** _they describe the architecture of the system, so how the system is decomposed and organized into components, the interfaces between these components. They also describe these components into a level of details that is suitable for allowing their construction._

![image](res/15.png)

## Implementation

What we do in this phase is taking care of realizing the design of the system that we just created and create an actual software system.

There are four fundamental principles, four pillars that can affect the way in which software is constructed:

- `Reduction of complexity` this aims to build software that is easier to understand and use.

- `Anticipation of diversity` which takes into account that software construction might change in various way over time. i.e, software evolves. In many cases, it evolves in unexpected ways. And therefore, we have to be able to anticipate some of these changes.

- `Structuring for validation` also called _design for testability_, it means that we want to build software so that it is easily testable during the subsequent validation and verification activities.

- Finally and that is especially true within specific organizations and or domains. It is important that the `software conforms to a set of internal or external standards.` And some e.g, of this might be internal standards, coding standards within an organization, or naming standards within an organization, etc.

![image](res/16.png)

## Verification & Validation

It is that phase of software development that aims to check that the software system meets its specification and fulfill its requirements.

**Validation** activity that answers the question `did we build the right software system?`. Did we build the system that the customer wants? That will make the customer happy.

**Verification** answers the different question which is `did we build the system right.` So given a description of the system that is the one that we derived from the customer through the collection of requirements and then design and so on, did we a system that actually implements the specification that we defined? Verification can be performed at different levels.

- In particular, it can be performed at `Unit Level` in which we test that the individual units work as a expected.

- Can be performed in the `Integration Level` in which we test is the interaction between the different units. So we want to make sure that the different modules talk to each other in the right way.

- And finally, there is `System Testing` in which we test the system as a whole and we want to make sure that all the system, all the different pieces of the system work together in the right way. And this is also the level at which then we will apply validation and some other testing techniques like stress testing or robustness testing and so on.

![](res/17.png)

## Maintenance

As we known software development efforts normally result in the delivery of a software product that satisfies the user requirements.

So normally our software development organization will release this application to its final users, however, once the software is in operation many things can happen.

**for e.g,** the environment might change, there might be new systems in which our software has to operate. Or they may be feature requests, so the users man find out that, guess what, they want to do something different with the problem that we gave them. Or, again, and this is one of the most common occurrences, users might find problems with the software and may file bug reports and send the bug reports back to the software developer. These are the reasons why software maintenance is a necessary phase in software development.

`Software Maintenance` is the activity that sustains the software product as it evolves throughout its life cycle, specifically in response to bug reports, feature requests and environment changes development organizations perform three kinds of maintenance activities:

- `Corrective maintenance` to eliminate problems with the code.
- `Perfective maintenance` to accommodate feature request, and in some cases just to improve the software, for e.g, to make it more efficient.
- `Adaptive maintenance` to take care of the environment changes.

![](res/18.png)

After these activities are performed, the software developer will produce a new version of the application, will release it and the cycle will continue through our the lifetime of the software.

That's why maintenance is a fundamental activity and a very expensive one. And one of the reasons why maintenance is expensive, is `regression testing` during maintenance every time you modify your application you have to regression test the application, where regression testing is the activity re-testing software after it has been modified to make sure that the changes performed to the software work as expected, and that _changes did not introduce any unforseen effects._

**for e.g,** a version of software being released and just a couple of days later another version being released to fix some problems that occur with the new version. These problems is called as regression testing.

**Q. What are the traditional software phases?**

    [❌] Requirements engineering, design, abstraction, implementation, verification & validation.
    [❌] Design, optimization, implementation, verification & validation, maintenance.
    [✅] Requirements engineering, design, implementation, verification & validation, maintenance.

## Software Process Model Introduction

Also called as `Software Lifecycle Model.`

_It is a prescriptive model of what should happen from the very beginning to the very end of the software development process._

The main function of the life cycle model is to _determine the order of the different activities_ so that we know which activities should came first and which ones should follow.

Another function is to _determine the transition criteria between activities._ So, when we can go from one phase to the subsequent one. In other words, what the model should describe is what should we do next in and how long should we continue to do it for each activity in the model.

![](res/19.png)

## Waterfall Model

- Waterfall model is the `grandfather` of all the lifecycle models.

- In the waterfall model the project `progresses to an orderly sequence of steps.` From the initial software concept, down until the final phase.

- At the `end of the each phase` there will be a `review to determine` whether the project is `ready` to advance to the `next phase`.

- The pure waterfall model `performs well` for` softer products` in which there is a `stable product definition.` The domain is well known and the technologies involved are well understood. In these kind of domains, the waterfall model helps us to find errors in the early, local stages of the projects.

  ![](res/20.png)

**Advantages:**

- It allows us to find errors in the early stages of the project or easily.

**Disadvantage:**

- It is not very flexible. Normally, it is difficult to fully specify requirements at the beginning of the project. And this lack of flexibility is far ideal when dealing with project in which requirements change, the developers are not domain experts or the technology used are new and evolving, that is it is less than ideal for most real world projects.

## Spiral Process

It was first described by `Barry Boehm` in his paper from `1986` that was entitled `Spiral Model of Software Development and Enhancement.` And one of main characteristics of that paper is that it was describing the spiral model using a diagram.

![](res/21.png)

These diagrams has become very very popular.

The Spiral model is an `incremental risk-oriented lifecycle model` that has four main phases listed as follows:

- Determine Objectives
- Identify and resolve risks
- Development and Tests
- Plan the next iteration

A software project will go through these four phases in an iterative way.

- In the `first phase`, the requirements will be gathered.
- In the `second phase`, the risks and the alternate solutions will be identified, and a prototype will be produced.
- Software and tests for the software are produced in the development and test phase, which is the `third phase`.
- Finally, `fourth phase`, the output of the project is evaluated and the next iteration is planned.

`Spiral process` prescribes is a way of developing software by going through these phases in an iterative way, in which we learn more and more of the software, we identify more and more and account for more and more risks and we go more and more towards our final solution, our final release.

__Advantages:__

- Extensive risk analysis does reduce the chances of the project to fail. So there is a risk reduction advantage.
- Functionality can be added at a later phase because of the iterative nature of process.
- Software is produced early in the software lifecycle. So, at any iteration we have something to show for our development. We don't wait until the end before producing something.
- Get early feedback from the customer about what we produced.

__Disadvantages:__

- The risk analysis requires highly specific expertise.
- And unfortunately, the whole success of the process is highly dependent on risk analysis.
- It is way more complex then the waterfall model.
