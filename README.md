# Points🌟


## General
The importance rate is higher after Ch.6

Example details is not included

## SDLC (Ch.1)

Systems Developement Life Cycle:

- Planning
- Analysis
- Design
- Implementaion
  - Coding
  - Documentaion
  - Training Procedures
- Maintenance

## Agile (Ch.1)

### Principles

1. Instead of predicting things, it is more effecitve to adapt with the situation.
2. People are more a key point than roles.
3. Self-adaptive processes.

### Use Agile When...

1. It is **impossible to predict** the needs of the project.
2. You have a **experienced and responsible** development **team**.
3. **Customers** are glad to get **involve** to the development process.

## Outsourcing (Ch.2)

Turning over some or all of the responsibility of an organization's information systems applications/operations to outside firm.

## Project Risk Factors (Ch.5)

- Project Size
- Project structure
- Dvelopment Group
- User Group

Generally,

project size ~ risk

requirement structured and ease to obtain level ~ !risk

standardized level ~ !risk

user familiarity ~ !risk

## Object Oriented Tech. (From Guest Slides)

### Priciples

1. Encapsulation 封装

  - 隐藏对象的内在复杂度，对外给出简单的接口
  
2. Modularity 模块化

  - 将复杂的问题分开成数个简单的问题，分开解决
  
3. Hierachy 继承

  - 将同一种对象的共同行为一般化
  
4. Abstraction 抽象
  
  - 同样结构的对象可以有不同的行为，但是他们可以由相同的接口表示
  - Objects with a same structure can have different behaviours, but they can still be represented by one abstract interface.

## Methodology Selection (CMS.pdf)

first 4-5 pros and cons, getting the key points is fine. Ignore the Incremental. 

### Waterfall

#### Pros

1. Supports **less experienced or less stable** project teams/managers.
2. Ensure the **orderly sequence** of development steps and strict controls for ensuring quality.
3. Progress of project development is **measurable**.
4. **Save resources**.

#### Cons

1. **Inflexible, slow, costly and cumbersome(big&heavy)** beacuse of tight control.
2. In most cases the project cannot **move backward**.
3. Be difficult to **iterate**.
4. Depend on early declarations of requirement, which may not be easy to be defined early in the project.
5. Unexcepted situations often happen during design and coding.

#### Use Waterfall When...

1. Developig a mainframe-baed or transaction-based batch system.
2. Developing large, expensive and complicated system.
3. Development don't need to finish immediately.
4. Project has clear objective and solution.
5. Requirements can be declared clearly.

### Prototyping

Prototyping is not a standalone development methodology. 
It is used to manage some parts if another complete methodology.

#### Pros

1. Be able to solve the problem that users cannot clearly tell their needs, as well as the problem that analysts cannot understand user's need. (via providing a tentative(sth. in draft) for experimental purposes.)
2. Improves user paticipation in system developement.
3. Useful for resovling unclear objectives.
4. Can use knowledge exported from early iterations. (❓)

#### Cons

1. Not being strict.
2. Problem analysis may be incomplete and thus only the most obvious and **superficial**(not being deep) needs will be addressed, resulting inefficient practices being easily built into the new system.
3. Requirements may frequently change significantly.
4. Identification of non-functional elements is difficult to document.(❓)
5. Designers may neglect documentation, resulting in insufficient justification for the final product and inadequate records for the future. (Why they will have narrow focus when they prototype quickly?)

#### Use Prototyping When...

1. Project is for development of an online system requiring extensive user dialog, or for a less well-defined expert and decision support system. (Means that they are not very deepin systems?)
2. Project is large with many users, interrelationships and functions. (For reducing risk relating to requirement definition)
3. Project objectives are unclear.
4. Project need to be implemented quickly.
5. Project requirements will change frequently and significantly (By users which are all Gods).

### Spiral

Combination Linear and Iterative.

#### Pros

1. Enhanced risk avoidance.
2. Helpful for selecting the best methodology of a given iteration.
3. Can use different methodologies in different iteraion, based on the risk factors..

#### Cons

1. It is a challenge to determine methodology for each iteration.
2. Being very complex due to its high constomization level.
3. Each cycle may generate more work for the next one, and this is not controlled.
4. No clear termination condition.
5. May need a experienced manager.

#### Use Sprial When...

1. Developing real-time and safety critical systems.
2. Risk avoidance is very important in the project.
3. It is less important to save money.
4. Project manager is skillful and experienced.
5. Requirement exists for strong approval and documentation control.

### RAD
😈

#### Pros
**FAST, CHEAP, READILY(FOR ALL), FLEXIBLE**

#### Cons
Developed system may not satisfy the business requirement.

lower quilty, inconsistant design, may add more and more features

#### Use RAD WHEN...

1. Project is of **small-to-medium scale** and of short duration
2. Project scope is **focused**, such that the business objectives are well defined and narrow.
3. Application is highly interactive, has a clearly defined user group, and is not **computationally complex**.
4. Functionality of the system is **clearly visible at the user interface**.


## SSM - Soft System Methodology (Topic 9)

### CATWOE

- Customers
- Actors
- Transform
- Worldview
- Owner
- Environmental Constraint

#### Example - iPhone

- Customers: iPhone device users
- Actors: Designers and engineers from Apple
- Transform: Jobs only available on desktop -> Jobs available even in toilet
- Worldview: People can only work near the desk with keyboard and pen, which is not convenient
- Owner: Apple Inc.
- Environment: Battery, Wireless Network, etc.
