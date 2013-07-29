# Security Principles

What a wonderful surprise; I am overwhelmed by the interest people have already shown in this project.

Inevitably applications are designed with security principles architects knew about, security folks included. 
However, as this project demonstrates there are far more than just a 'few' principles; most of which never make it into the design.

For example, security design happens with perhaps a [handfull of principles](https://www.owasp.org/index.php/Category:Principle):

* least priviledge
* perimiter security
* defense in depth
 
As a result we reguraly see designs without ***seperation of priviledge***. 

Think about that, *most* web applications today have all their eggs in a single basket.

The business logic, the identities, passwords, products, policy enforcement, security rules are all found in the same applicaiton database that makes up the typical website!
It is little wonder then, that attacks on the database have been so completely devistating, since there is no seperation of priviledge!

I hope that with this project we can identify and describe a minimum functional set of principles that must be present in a secure design; and I hope you will join me.

## Participation 

I strongly encourage you to participate and contribute. 
I have no monopoly on this knowledge. However, we all have pieces of this knowledge from our experience, so lets begin with putting our individual pieces together and make something great. Great things happen when people work together. :-)

## About the project 

Over the course of my career, I have come across and collected a number of security 'aphorisms.'  These aphorisms constitute the fundamental principles of information security.  

None of the ideas or truths are mine and unfortunately, I did not collect the citations. Initially, I would like to identify the correct citations for each aphorism. 

Additionally, many are restatements of the same idea; thus the 'collection of ideas' defines a fundamental principle. As such, I would also like to reverse engineer the principles from the aphorisms where appropriate as well.


## Purpose

The end goal is to identify and cite and document the fundamental principles of information security. Once, this is well organised, I think it would be great to publish this via [OWASP Press](http://scriptogr.am/dennis-groves/post/owasp-press).
Of course, it will *always* remain freely availible, and any money collected will goto either directly into the project to absorb costs, with any remaining funds going to the OWASP Foundation. 

This document shoud serve to guide technical architects and designers in the fundimental principles of security. 
