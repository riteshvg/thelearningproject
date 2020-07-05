---
template: post
title: var vs let vs const
slug: var-let-const
draft: false
date: 2020-07-05T14:00:37.639Z
description: What is the difference between var, let and const in JavaScript?
  And when should we use one vs the other?
category: javascript
tags:
  - javascript
  - development
  - self-learning
---
I was introduced to programming at a very later stage in my life. Precisely 2016 when I joined Adobe India as a Tech Consultant for their Experience Cloud. 

So the aspects of JS programming were all together new to me when I fired up the Code Editor and started staring at the massive piece of code for one of the JS file that I stumbled across. In this file most of the variables were declared using the var keyword (short for variable). In my naive outlook, I assumed that var was the only way to declare a variable. Ignoring the fact the EcmaScript 2015 (ES6) was already released that had introduced two new ways of declaring  a variable (let and const). 

It's only when I chanced upon a blog by Tania Rascia ([ES6 Syntax and Feature Overview](https://www.taniarascia.com/es6-syntax-and-feature-overview)) that I understood what I had been practicing all along is already a past method. According to her article, var should be avoided as much as possible as it is legacy. The other two methods of declaring a variable (let and const) have their own use cases. 

const is the most ideal method for declaring a variable. Which means we should no longer be starting our code with 

var a = 1;

but const a = 1;

and let should be used only in case of declaring loops

let a = 1

if(a){

let a = 2;\
  console.log(a); \
}

Today it is common to declare a vast majority of variables using const instead of  let/var. The reason is because const will throw an error if an attempt is made to change its value after it has been declared. This is a useful feature to prevent accidental mutation. 

> I think that is all I need to know and remember. Stop using var and start using const for most of the variables, and use let only when we are creating a loop.