# Introduction
In this section I want to explain:

1. What is Domain Driven Design?
2. Why it is important to consider using it when developing applications?
	* Know where it is important to invest, apply a model
	* Better estimate the cost and risk of a change
		* In the core domain?
3. How it can help to build better software from a functional and architecture point of view?
4. What's a domain?
5. What's a model?


The Domain Driven Design is an approach of software development that helps you to create better software in a better way.

It will first help you to better understand the problems of your domain. In orther words the business rules, policies and other concepts of the area of which the program applies to.


Domain Driven Design will next help you to design solutions for these problems. It will helps you to isolate core parts in order to have stability and allowing evolution.

## What's a domain?
*Domain* is the name given to the area of knowledge to which the problems applies.

## What's a model?
In order to solve problems you will create a model of your domain.
A Model belongs to the solution space. A model is a simplification of the reality in order to abstract only concepts relevants to solve the probelms. 

**#isolation**, **#evolution**, **#stability**, **#synergy** between model and problems.

## Ideas to better apply DDD

### Organise domain workshop / trainings

The more important is to understand the subject area for which you are building software. For instance for a consumer loan company an important point would be to understand what are the types of loans? 

### Service company

When you are a service company things become complicated. The domain could seems the same at first sight but it is definitely not. In a multi-tenant application the domain of your application has a parameter more: the **provider** aspect.

### Ubiquitous Language

Discuss about domain and identify if there are concepts with several names of a name with several meaning depending on the context. Then define a dictionnary of all allowed terms.
