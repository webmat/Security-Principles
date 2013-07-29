# Security Principles

What a wonderful surprise. I am overwhelmed by the interest people have already shown in this project.

Inevitably applications are designed with security principles architects knew about, security folks included. 
However, as this project demonstrates there are far more than just a 'few' principles, most of which never make it into the design.

For example, security design happens with perhaps a [handful of principles](https://www.owasp.org/index.php/Category:Principle):

* least privilege
* perimeter security
* defence in depth
 
As a result, we regularly see designs without ***separation of privilege***. 

Think about that, *most* web applications today have all their eggs in a single basket.

The business logic, the identities, passwords, products, policy enforcement, security rules are all found in the same application database that makes up the typical website!
It is little wonder then, that attacks on the database have been so completely devastating, since there is no separation of privilege!

I hope that with this project, we can identify and describe a minimum functional set of principles that must be present in a secure design. I hope you will join me.

## Participation 

I strongly encourage you to participate and contribute. 
I have no monopoly on this knowledge; however, we all have pieces of this knowledge from our experience. Let's begin with putting our individual pieces together and make something great. Great things happen when people work together. :-)

## About the project 

Over the course of my career, I have come across and collected a number of security 'aphorisms.' These aphorisms constitute the fundamental principles of information security.  

None of the ideas or truths are mine, and unfortunately, I did not collect the citations. Initially, I would like to identify the correct citations for each aphorism. 

Additionally, many are re-statements of the same idea; thus, the 'collection of ideas' defines a fundamental principle. As such, I would also like to reverse engineer the principles from the aphorisms where appropriate, as well.


## Purpose

The end goal is to identify, cite, and document the fundamental principles of information security. Once this is well organised, I think it would be great to publish this via [OWASP Press](http://scriptogr.am/dennis-groves/post/owasp-press).
Of course, it will *always* remain freely available, and any money collected will go directly into the project to absorb costs with any remaining funds going to the OWASP Foundation. 

This document should serve as a guide to technical architects and designers outlining the fundamental principles of security. 
