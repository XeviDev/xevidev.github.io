---
title: SOLID Principles
date: 2023-03-21 21:42 +0100
categories: [Good manners]
tags: [good manners]     # TAG names should always be lowercase
author: <author_id>
---
The **SOLID Principles** are five principles of Object-Oriented class design. They are a set of rules and best practices to follow when designing a class structure.

The **5 SOLID principles** of software application design are:

- **S** – Single Responsibility Principle (SRP)
- **O** – Open/Closed Principle (OCP)
- **L** – Liskov Substitution Principle (LSP)
- **I** – Interface Segregation Principle (ISP)
- **D** – Dependency Inversion Principle (DIP)

In this sense the application of SOLID principles is closely related to the understanding and use of design patterns, which will allow us to maintain **high cohesion** and therefore **low coupling** of software.

# **What are cohesion and coupling?**

These are two very relevant concepts when designing and developing software. Let's see what they are.

## **Coupling**

Coupling refers to the **degree of interdependence that two software units have on each other**, meaning by software units: classes, subtypes, methods, modules, functions, libraries, etc.

If two software units are completely independent of each other, they are said to be decoupled.

## **Cohesion**

Software cohesion is the **degree to which different elements of a system stay together to achieve a better result** than if they worked separately. It refers to the way in which we can group various software units together to create a larger unit.

# **SOLID Principles**

## **Single Responsibility Principle**

As the name implies, it states that a class, component or microservice should be responsible for only one thing (the much-acclaimed term "decoupled").

## **Open/Closed Principle**

We need to be able to extend the behaviour of our classes without needing to modify their code.

This helps us to keep adding functionality with the assurance that it will not affect existing code. New functionality will mean adding new classes and methods, but in general it should not mean modifying what has already been written.

## **Liskov's Substitution Principle**

Liskov's substitution principle tells us that if somewhere in our code we are using a class, and that class is extended, we must be able to use any of the child classes and the program must still be valid.

This forces us to make sure that when we extend a class we are not altering the behaviour of the parent.

## **Interface Segregation Principle**

The principle of interface segregation means that no class should depend on methods that it does not use. Therefore, when creating interfaces that define behaviours, it is important to be sure that all classes that implement those interfaces will need and be able to add behaviours to all methods. Otherwise, it is better to have several smaller interfaces.

## **Principle of Dependency Inversion**

Thanks to the principle of dependency inversion, we can make the code that is the core of our application not depend on implementation details, such as the framework you use, the database, how you connect to your server... All these aspects will be specified by interfaces, and the core will not have to know what the actual implementation is in order to work.

All these aspects will be specified by interfaces, and the kernel will not have to know what the actual implementation is in order to function.

The definition that is usually given is:

> - High-level classes should not depend on low-level classes. Both should depend on abstractions.
> - Abstractions should not depend on details. Details should depend on abstractions.

# **Bibliography**

[https://devexperto.com/principios-solid/](https://devexperto.com/principios-solid/)

[https://profile.es/blog/principios-solid-desarrollo-software-calidad/](https://profile.es/blog/principios-solid-desarrollo-software-calidad/)