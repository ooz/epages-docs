---
layout: post
title: "First Jena Devlopers Meetup: Docker Party!"
date: "2016-04-11 13:37:42"
icon: cubes
categories: events
authors: ["Benjamin and Oliver Z."]
---

On the first Thursday of April the newly founded Softwerkskammer Jena had its first Developers Meetup. 
ePages took the opportunity to be the event host and provide not just conference rooms and serveral workstation laptops but also free pizza, snacks, Club-Mate and some other refreshments for everyone.
Over 30 attendees from a dozen of companies from the area of Jena followed the invitation to the Docker Party and joined the orga team for 4 hours of coding fun from 6 pm until nearly 10 pm with an open end at the local pub, where the devotedly discussions lasted until 2 am in the morning.

## Agenda

At the beginning there was a short period of spare time for meet and greet and a brief introduction about the Softwerkskammer, its current distribution and helpful contact information followed. 

Then the Docker Party itself launched! It consisted of an one hour of technological introduction talk with some short demonstration and and 3 workshops for all skill levels and some free time to network.



Still to many sentences listing a series of items, topics. 
Enjoyed listening to talks and coding along in serveral prepared workshops for different skill levels. 
Currently the organization team consists of 8 developers. 

Their time with the newly founded Softwerkskamer Jena - a local Software Craftsmanship Community.

The meetup took place in the ePages Jena office. The company provided conference rooms, demo machines, snacks, various drinks and pizza.
Despite the short notice 35 attendees including 8 supporters from ePages followed the call. 
The participants were a diverse group of local and transstate developers (from demq), freelancers and college students.

[//]: # (ePages hosted the first Softwerkskammer Jena meetup last thursday)
[//]: # (the Softwerkskammer is a group of developers caring about software craftsmanship)
[//]: # (the topic of the meetup was Docker (due to recent Docker bday, growth, importance and use in the company))
[//]: # (despite short notice: 35 attendees)


## The Talk

After a short introduction about the Softwerkskammer and Docker in general, the talk focused on basic commands, use cases and best practises. 
The latter were based on the [official Docker recommendations](https://docs.docker.com/engine/userguide/eng-image/dockerfile_best-practices), tips by [Michael](http://crosbymichael.com/dockerfile-best-practices.html) [Crosby](http://crosbymichael.com/dockerfile-best-practices-take-2.html) as well as our experiences with developing, testing, integrating, deploying and running a large e-Commerce platform.

If you missed the presentation you can look it up on [GitHub](https://github.com/jenadevs/jenadevs-meetup-001-docker-party).

## Containers, Containers, Con... err Workshops, Workshops, Workshops!

* meetup was intended to be more than a talk: attendees should 

* 3 workshops for 3 years of Docker

  1. beginners: docker bday app and tutorial
  2. advanced: build your own dockerfile/image
  3. special: coresos
  
* wait: a 4th "workshop": Docker in Docker
* for the special session some machines were prepared 

## Beginner Workshop

The goal of the beginner workshop was to setup the Docker environment, learn the basic commands, run the workflow and get familiar with Docker Compose.
For this the participants followed the [official Docker birthday tutorial](https://github.com/docker/docker-birthday-3/blob/master/tutorial.md) while the more experienced ePagees Benjamin Nothdurft and Kay Abendroth offered assistance.
As kittens bustled around the screens, the Docker newbies built simple web applications using the Python microframework [Flask](http://flask.pocoo.org/) -- all running in a container, of course.

## Advanced Workshop

This workshop focused on writing your own Dockerfiles and testing the build of the image and run the containers with CircleCI. Bastian Klein prepared a empty Dockerfile and Circle file with comments only, where he had removed the implementation. The attendes then had to figure out how the Dockerfile commands needed to be configured under the guidance of the workshop maintainer.

## Special Workshop

The most expierenced Dockers gathered together in workshop, where the main foxus was abit shifted. We had prepared three worstation laptops. And Andreas Grohman introduced CoreOS to the each participant. The goal was to setup a cluster environment with three nodes and run Docker on it. Everyone succeeded.

Afterwards Christian Köhler gave an insight on how to configure Kubernetes with a short demonstration. He also distinctly outlined the advantages to Docker Swarm.

## Summary and Outlook

* try to install this as a regular platform: first thursday every month
* next up: coding dojo with a kata
* after that: functional programming

Thanks to all attendees and ePages coworkers for making this happen!
