# Introduction
In this section I want to explain:

1. What is Domain Driven Design?
2. Why use this approache to develop applications?
	* Know where it is important to invest, apply a model
	* Better estimate the cost and risk of a change
		* In the core domain?
3. How it can help to build better software from a functional and architecture point of view?
4. What are domain and sub-domain?
5. What's a domain model?

## What's DDD?
The Domain Driven Design is an approach of software development that helps you to create better software in a better way.

Every software exists to solve problems. The subject area in which these problems exist is the domain of your application. All business concepts, rules and policies your code manipulates comes from the domain. In order build good software the more important is to understand the problem space for which you are building software.

The Domain Driven Design philosophy provides patterns, practices and principles in order to manage the complexity of creation and maintenance of an application by creating synergies between the problem space and the solution space.

In order words, the Domain Driven Design will help you to better understand your domain, design solutions and implement them.

## How DDD helps in the problem space?
The Domain Driven Design provides some *strategic* patterns in order to:

1. better understand the problem space: the domain;
2. shape the solution. 

They will next help us to shape the solution space: the application.

It is probably the most important part of the Domain Driven Design approach.

* Identifying what is really important: it will helps you to isolate core parts in order to have stability and allowing evolution.
* Creating models
* Defining a common language
* Isolating for stability
* Communicating the big picture

## How DDD helps in the solution space?
The Domain Driven Design provides some *tactic* partterns also called "the building blocks". These patterns will help you to implement solutions.

## What's a domain?
*Domain* is the name given to the area of knowledge to which the problems applies.

## What's a model?
In order to solve problems you will create a model of your domain.
A Model belongs to the solution space. A model is a simplification of the reality in order to abstract only concepts relevants to solve the probelms. 

## What's an analysis model?

**#isolation**, **#evolution**, **#stability**, **#synergy** between model and problems.

## Ideas to better apply DDD

### Organise knowledge crunching sessions

The more important is to understand the subject area for which you are building software. For instance for a consumer loan company an important point would be to understand what are the types of loans? 

### Service company

When you are a service company things become complicated. The domain could seems the same at first sight but it is definitely not. In a multi-tenant application the domain of your application has a parameter more: the **provider** aspect.

### Ubiquitous Language

Discuss about domain and identify if there are concepts with several names of a name with several meaning depending on the context. Then define a dictionnary of all allowed terms.
