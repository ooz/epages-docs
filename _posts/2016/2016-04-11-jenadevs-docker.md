---
layout: post
title: "First Jena Devlopers Meetup: Docker Party!"
date: "2016-04-11 13:37:42"
icon: cubes
categories: events
authors: ["Benjamin and Oliver Z."]
---

On the first Thursday of April the newly founded [Softwerkskammer Jena](https://www.softwerkskammer.org/groups/jena) had its first [Developers Meetup](www.meetup.com/jenadevs). 
ePages took the opportunity to be the event host and provide not just conference rooms and serveral workstation laptops but also free pizza, snacks, Club-Mate and some other refreshments for everyone.
Despite the short notice over 30 attendees from a dozen of companies from the area of Jena, university students and even some freelancers followed the invitation to the Docker Party. 
They joined the orga team of 8 developers for 4 hours of coding fun from 6 pm until nearly 10 pm with an open end at the local pub, where the devotedly discussions lasted until 2 am in the morning.

## Agenda

At the beginning there was a short period of spare time for meet and greet as well as a brief introduction about the [Softwerkskammer](softwerkskammer.org) – the german part of the [Software Craftsmanship Community](http://manifesto.softwarecraftsmanship.org) – and its current distribution with some helpful contact information like the [@jenadevs](https://twitter.com/jenadevs) account on Twitter. 

Then the Docker Party, which celebrated the [3rd birthday of Docker](https://www.docker.com/community/docker-birthday-3), was launched! 
It consisted of an one hour talk including a demo to introduce the technological foundation and nearly three hours of different workshops for every skill level:

  1. **Beginner:** The official Docker birthday app tutorial
  - **Advanced:** Building your own Dockerfile with integration tests after best practises
  - **Special:** CoresOS Cluster Workshop
  - **Hidden - also known as exploding kittens:** Orchestration Workshop by [Jérôme Petazzoni](https://twitter.com/jpetazzo), the creater of [Docker-in-Docker](https://github.com/jpetazzo/dind) 

## Introduction talk with demo and best practises

The talk in the first place focused on the Docker basics, the components of the Docker ecosystem and the general tooling workflow of building images, running containers and pushing them to the Docker Hub. 
Afterwards the basic commands were demonstrated with some live coding on the terminal, where several containers were also inspected at runtime.
The second part of the talk considered some best practises for wrtiting your own Dockerfile, which was based on the [official Docker recommendations](https://docs.docker.com/engine/userguide/eng-image/dockerfile_best-practices), tips by [Michael](http://crosbymichael.com/dockerfile-best-practices.html) [Crosby](http://crosbymichael.com/dockerfile-best-practices-take-2.html) as well as the experiences of [epagesdevs](http://twitter.com/epagesdevs) with developing, testing, integrating, deploying and running supportive images for our eCommerce platform. 
This was a good entrypoint to also show some of our typical use cases at ePages, e.g. in the Continuous Delivery Pipeline, at integration testing or in the Operations area for our own and provider infrastructure which also relies on [Kubeneretes](http://kubernetes.io). To finish the talk some typical base images and official app environment images were discussed, too. 

## Containers, Containers, Con... err Workshops!

Upfront, all necessary material and code for the workshops was hosted on the jenadevs [GitHub](https://github.com/jenadevs) account which even offers the [complete presentation](https://github.com/jenadevs/jenadevs-meetup-001-docker-party). Great news: _All material of **[jenadevs](https://github.com/jenadevs)** is free and will always be open-source!_

### Beginner Workshop

The goal of the beginner workshop was to setup the Docker environment, learn the basic commands, run the workflow and get familiar with Docker Compose.
For this the participants followed the [official Docker birthday tutorial](https://github.com/docker/docker-birthday-3/blob/master/tutorial.md) while the more experienced Docker users, Benjamin Nothdurft and Kay Abendroth offered assistance.
As kittens bustled around the screens, the Docker newbies built simple web applications using the Python microframework [Flask](http://flask.pocoo.org/) -- all running in a container, of course.

### Advanced Workshop

This workshop focused on writing your own Dockerfiles and testing the build of the image and run the containers with [CircleCI](https://circleci.com). Bastian Klein prepared an empty Dockerfile and Circle.yml with comments only, where he had removed the implementation. The attendes then had to figure out how the Dockerfile commands needed to be configured under the guidance of the workshop maintainer.

### Special Workshop

The most experienced Dockers gathered together in the special workshop, where the main focus was a bit shifted. We had prepared three worstation laptops. And Andreas Grohman introduced CoreOS to the each participant. The goal was to setup a cluster environment with three nodes and run Docker on it. Everyone succeeded.

Afterwards Christian Köhler gave an insight on how to configure Kubernetes with a short demonstration. He also distinctly outlined the advantages to Docker Swarm.

## Summary and Outlook

* try to install this as a regular platform: first thursday every month
* next up: coding dojo with a kata
* after that: functional programming

Thanks to all attendees and ePages coworkers for making this happen!
