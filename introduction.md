# Introduction
In this section I want to explain:

1. What is Domain Driven Design?
2. Why use this approache to develop applications?
	* Know where it is important to invest, apply a model
	* Better estimate the cost and risk of a change
		* In the core domain?
	* Why should I use Domain Driven Design?
	* What does it change in my habits?
	* Why should I spend time to learn it?
	* Is it a hard process?
3. How it can help to build better software from a functional and architecture point of view?
4. What are domain and sub-domain?
5. What's a domain model?

## Why DDD?

> *Any fool can write code that computers can understand. Good programmers write code than humans can understand - Martin Fowler*

* The application works approximativaly we're not sure how?
* There is always communication problems between stakeholders and developers resulting of an applications that doesn't do the job
	* Ambiguities: "Oh no I did not talk about that case, only this one!"
* When we talk about business concept it is not always easy to translate it to solution concept. How this class resolving this kind of business stuff is named?
* Where the fuck is this class?
* New developer are totally lost?
* We don't know how to integrate new developer?
* Fragility? Class that does a lot of things? Messy and buggy?
* I don't know what that code do nor how it do what it do. All of what I know is that if it returns something wrong we have a serious problem.
* At the start => ok
* The evolution of business feature => complexity
* Developer turn over 
* Software does not fully achieve its objectives
** bugs
* Unstructured design
* Lack of a common terms
* Lack of a common understanding
* You don't find where in the code is a fucking business artifact

## What's DDD?
Domain Driven Design is a development approach having a set of patterns, practices and principles that will help you to manage the complexity of large entreprise applications.

Every application exists only to solve real life problems. The success of a software can be measured by how well it helps its users.

In order to deliver great software we have first to understand what the problems are and the context in which they exist. In the Domain Driven Design philosophy this context is referred as the *domain* of your application.

DDD tackles the complexity by creating synergies and bindings between the the problem space and the solution space. 

Some DDD tools will help you in the understanding of the problem space (the problems and their domain) while other will serve as guides for the software design and development.

DDD encourages the discussion and the colloaboration with *domain experts* in order to learn about the domain. From these discussion born an *ubiquitous language* between all parties - a common vocabulary that is shared and understand by every body. Every business artifact that matter in the problem solving can be precisly identified and named.

This *ubiquitous language* will be the foundation of the analysis model. The analysis model is a projection of the domain. This projection is named a *domain model*. A *domain model* abstracts only what it is important in order to solve the problems for which we are developing the software.

The *ubiquitous language* acts as a binding between the problem space and the solution space. It is the guarantor of the synchronisation between the domain its model.

When well implementted DDD assures that the way the software is design is exactly how the software works. The domain model is propulsed directly to the heart of your applications.

*Knowledge crunching* session with domain expert will just provides you deeper insight into the domain which is an opportunity to evolve the model by *refactoring* it. The *model refinment* is an *iterative* process.

*Distillation* of your domain knwoledge will helps you to identify what parts of your domain that matter. By identifying the *core domain*, the *supporting domains* and the *generic domains* you will better know the where to put more attention, effort and resources.

DDD contains tacticals patterns in order to realise effectively the solution space. These *tacticals patterns* are also called the DDD's *building blocks*.

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


### Requirements
* Want to learn
* Want to build high quality software


Always start