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
Domain Driven Design is a development approach having a set of patterns, practices and principles that will help you to manage the complexity of large entreprise applications.

Every application exists only to solve real life problems. The success of a software can be measured by how well it helps its users.

In order to deliver great software we have first to understand what the problems are and the context in which they exist. In the Domain Driven Design philosophy this context is referred as the *domain* of your application.

DDD tackles the complexity by creating synergies and bindings between the the problem space and the solution space. 

Some facets of the DDD will help you in the understanding of the problem space (the problems and their domain) while other will serve as guides for the software design and development. 

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



