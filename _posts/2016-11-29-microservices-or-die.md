---
layout: post
title: Microservices or die?
comments: true
---
I'm still hearing that we need build microservices. I saw presentation which some smart guy talked about infrastrucute in his company.
They started from 2 monolith and now they have more than 100 microservices (and super compilcated deploy tool).
He said that they're planning to increase number of microservices to 200 because when we had 200 microservices would be "fancy" and "pro" and their business would run better.

I think this is ridiculus, why tech companies builds that amount of microservices?
I like the idea of microservices but I don't understand why we **always** think that is a solution for everything.

A lot of architects think that they need separate microservice for every feature which would be easilly add to existing one. 

Ok, I've just added one, another microservice to my project although I could add that functionality to my core application.
But that is my personal project, not for money and I can sacrifice easy deployment process. Because it is for fun!

Summarizing, microservices isn't always recipe for every problem. Microservices can solve your problems but sometimes introduce new.
By the other hand, your application should be designed as a set of microservices because converting monolith to set of microservice is extremally hard.

But despite of all I think we have a lot of good tools for maintain microservices on the market and desgn **new** apps as a set of microservices is a the best option at the moment.