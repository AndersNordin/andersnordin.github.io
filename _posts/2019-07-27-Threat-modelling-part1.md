---
layout: post
title:  "Things learned from doing threat modeling - part 1"
date:   2019-07-27 11:25:00 +0200
categories: security-architecture threat-modeling
---
Working as a security architect I do threat modeling very often. Through the years I've stumbled upon different methods and frameworks, tools, games and presentations. In this series I will share things I wish I knew when I started with threat modeling. 

## Threat modeling, huh?
Threat modeling is about analyzing each component and data flow in your system in order to understand how someone or something can abuse it. This is done through different threat scenarios. By analyzing different threat scenarios one can add the necessary controls already in the design phase. 

## Why threat modeling
For non-security people it can be quite hard at first to see the value of doing threat modeling. I often compare threat modeling to reliability analysis, you wouldn't build and deploy an oil rig without doing countless simulations of each part and material. Same goes for software! 

### Cost saving
Discovering flaws and vulnerabilities early-on in the design phase is far more cheaper than discovering the problem latter. Problems that are discovered when the software is shipped to production must go through the whole process again and might delay the whole release. 

### Security awareness
Doing threat modeling together with the whole team can put security on the radar. Discussing security threat and controls can help raise the awareness in the whole group and that is quite important as there often many people involved when building a system.

### Improving security in your software
The primary objective of doing threat modeling is to build a secure design by identifying potential vulnerabilities and risks.

## Useful links
Finally, I want to share two good resources about threat modeling.

The first one is a book written by Adam Shostack. It is a well-written comprehensive guide to threat modeling: [Threat Modeling : Designing for Security](https://www.amazon.com/Threat-Modeling-Designing-Adam-Shostack-ebook/dp/B00IG71FAS)

If you are more into videos than books there is great walkthrough you can watch here: [Threat Modeling by Jim DelGrosso](https://www.youtube.com/watch?v=We2cy8JwVqc)

## Up next
In the following series I will cover:
- Methods for doing threat modeling
- Know your threat actor
- Useful tools when doing threat modeling
