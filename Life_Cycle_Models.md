# Life Cycle Models

## Introduction with Barry Boehm

![](res/12.png)

The bottom line is that choosing the right lifecycle model is fundamental importance.

## Traditional Software Phases

Software engineering is an important and critical discipline, concerned with cost effective software development. This is based on a systematic approach that uses appropriate tools and techniques, operates under specific development constraints. And most importantly, follows a process.

![](res/13.png)

## Requirements Engineering

It is a field within software engineering that deals with establishing the needs of stakeholders that are to be solved by software.

**Why is this phase so important?**

In general, the cost of correcting an error depends on the number of subsequent decisions that are based on it. Therefore, errors made in understanding requirements have the potential for greatest cost because many other design decisions depends on them and many other follow up decisions depend on them.

![](res/14.png)

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

![](res/15.png)

## Implementation

What we do in this phase is taking care of realizing the design of the system that we just created and create an actual software system.

There are four fundamental principles, four pillars that can affect the way in which software is constructed:

- `Reduction of complexity` this aims to build software that is easier to understand and use.

- `Anticipation of diversity` which takes into account that software construction might change in various way over time. i.e, software evolves. In many cases, it evolves in unexpected ways. And therefore, we have to be able to anticipate some of these changes.

- `Structuring for validation` also called _design for testability_, it means that we want to build software so that it is easily testable during the subsequent validation and verification activities.

- Finally and that is especially true within specific organizations and or domains. It is important that the `software conforms to a set of internal or external standards.` And some e.g, of this might be internal standards, coding standards within an organization, or naming standards within an organization, etc.

![](res/16.png)

## Verification & Validation
