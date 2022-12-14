---
layout: essay
type: essay
title: "The Language of the Web"
# All dates must be YYYY-MM-DD format!
date: 2022-08-30
published: true
labels:
  - Javascript
---

*A slightly scattered, initial review of Javascript*

Javascript as a language has the reputation of being the so-called, "language of the web."  This, is certainly true. Javascript has many features that make it suitted for this role. It interacts well with HTML and CSS, and the emphasis on "functions as first class" allows for a developer to add in script tags to perform a specific task here or there throughout a webpage, without having to define a 'main.c' file, or an entire class file in Java.

As Javascript grew in popularity though, it feels -- to a newbie at least -- like the developers started add in too many new "features," making the final product seem cluttered.

## Syntax sugar

Syntax sugar is a term for certain bits of syntax added to languages, that don't actually add any new functionality to the programming language, but just provides the developer with a new way of expressing the same old task. 

While sometimes this can be convienient, when every operation in the language has three different ways to express the same operation, the task of learning a new language can become needlessly tiresome.

For instance, why do we need two different ways of accessing information in a Javascript object? One notation is perfectly fine, and does the job for us. Adding in a separate, equivalent notation can only result in confusion.

If ```let``` is to be used instead of ```var``` in essentially every case, why even learn about ```var```? I can understand keeping it the langauge for backwards compatability reasons, but if the stronger scoping is always to be used, why does freecodecamp teach first with ```var```?

Why do we really need new syntax to be introduced for deconstructing? While I understand that things might get tedious at times, tedium -- it seems to me -- us sometiems part of the job of a software developer. While adding new syntax can save time if one is used to it, it can -- and will -- add new errors for those that aren't used to it.

## Learning Curves

While there are certain aspects of programming and software engineering that are universal, and span different programming languages -- algorithmic thinking, functional or object oriented frameworks of thinking, a general knowledge built from experience of how to find and debug errors -- whenever someone decides to learn a new framework or language, there is always a learning curve.

My main complaint with syntax sugar, is that while it can help the expert, it steepens the learning curve for a newcomer.

## Type-casting

What's going on here man? It's an absolute nightmare that Javascript will willy-nilly convert things into strings in order to compare them to each other. Other languages have catch statements! So too does Javascript! Why not just use those when different typed bits of data are being compared!!

This is probably just me not yet being used to such a soft-typed language like Javascript. I don't know. Well see.

## Final Thoughts

Ultimately, it's exciting to be learning a new language. I do like how modular Javascript feels -- not everything has to be class, and not everything has to be run from a ```main``` file, but functions can pop in and out of existance and do helpful things on a webpage. I'm excited to learn more about how Javascript as a language interacts with other technologies and building-blocks of the web.
