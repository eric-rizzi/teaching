---
layout: post
title: "Independent Study"
date: 2024-09-29
categories:
    - Curriculum
    - High School
    - Python
    - JavaScript
    - ChatBots
    - AWS
    - Software Engineering
    - CI/CD
    - Artificial Intelligence
---

### Course Highlights

This independent course allows advanced students to work their way all the way
up to the creation of a modern web-app that calls an AWS hosted back-end. Along
the way, students will learn about key Python concepts to make their code less
buggy as well as software engineering techniques/best-practices that allows
their ideas to scale. The course relies heavily on both independent GoogleDoc
worksheets and the use of ChatBots to guide the student from the basics all the
way up to the cutting edge.

#### Years Taught

- [2024 - 2025](https://github.com/eric-rizzi/ucls-independent-study)

#### Main Links

- [Main Repository](https://github.com/eric-rizzi/ucls-independent-study)
- [Administrative Documents](https://github.com/eric-rizzi/ucls-ml-ai/tree/mainline/Administration)
- [Course Curriculum](https://github.com/eric-rizzi/ucls-independent-study)

#### Unit 0: Intermediate Python

![Fishy Game]({{ site.baseurl }}/assets/independent_study/fishy_game.png)

This unit serves as the entry point for the course. It is designed to quickly
get students up to speed in terms of what objects/classes are and how they work.
The goal is _just_ to get students proficient enough that they can understand
code that is being output by ChatBots in future lessons. It is **not** intended
to take the place of a real CS course on object-oriented programming.

In the unit, students will create their own versions of Pong and Fishy with the
help of worksheets. There is very tight integration between the worksheets and
the code that are using as their starting point. This is because they are using
the PRIMM method where students modify existing code before attempting to create
their own.

##### Keywords

Python, Grok, Pygame, Objects, Functions, PRIMM, Fishy, Pong

##### Resources

- [VSCode Setup Worksheet](https://docs.google.com/document/d/1rIdk_vk-tgh7_RPmZKn8qJc9L8iSBRDWfoNWK-HW5TA)
- [Pong Worksheet](https://docs.google.com/document/d/1eW4la2fCusx_mdwDf4gEzEPu_daq-ZIVavT85ASw3pc)
- [Object Basics Worksheet](https://docs.google.com/document/d/1rS0B1gvbGJEnMxNH8ZPs3ojfpMQOp3Cf3u1ARx2HDU0)
- [Fishy Worksheet](https://docs.google.com/document/d/1gsYWeewpQPB9gjoGOE963jIxD110brmhtM3Qjbk9Ao8)
- [Pong Repo](https://github.com/eric-rizzi/ucls-partial-pong)
- [Fishy Repo](https://github.com/eric-rizzi/ucls-fishy)

#### Unit 1: Command-Line

![Terminal with a cow on it]({{ site.baseurl }}/assets/independent_study/cow_say.jpg)

This unit provides students with the basic skills on the command-line required
to use the terminal in future units on `git` and `docker`. As with the previous
unit, the goal here is **not** to make them experts in the terminal to the point
where they can figure everything out by themselves. Instead, it is to get
students quickly up to speed so that they can then use a ChatBot to help them
discover the necessary commands for more difficult tasks.

##### Keywords

Terminal, Shell, Linux, GameShell

##### Resources

- [GameShell](https://github.com/phyver/GameShell)
- [Over the Wire](https://overthewire.org/wargames/bandit/)

#### Unit 2: Git

![Git Network Graph]({{ site.baseurl }}/assets/independent_study/git_graph.jpg)

This unit teaches students the basic concepts of `git`. In it, they will learn
how to set up a local repository and create simple, single branch projects. In
addition, they learn how to set up a remote repository in order to save and test
their work. Again, this unit is **not** intended to give students a complete
understanding `git`. Instead, since they are working alone, a lot of the
complexity can be hidden. This means that they can slowly increase their
understanding over the entire course, relying on the ChatBot to help them jump
over the small hurdles they encounter.

##### Keywords

Commits, GitLab, Conventional Comments, CI/CD

##### Resources

- [Today I Learned](https://github.com/jbranchaud/til)

#### Unit 3: Advanced Python

![Advanced Python Topics]({{ site.baseurl }}/assets/independent_study/one_liner.png)

This is the final "background concepts" unit for students. It is intended to
help them brush up on their Python and to understand the importance of types
when developing large, complex project. I chose comprehensions and generics very
specifically because most students won't have ever seen them and they provide a
good basis of discussion about the importance of having good, easy to
understand, difficult to break code.

##### Keywords

Python, Generic Types, Comprehensions, Objects

##### Resources

- [Comprehension Worksheet](https://docs.google.com/document/d/1zP6oDFBjCgp-V4EkReR_L5QZTUImNS-jG7E31c37T7M)
- [Generic Types Worksheet](https://docs.google.com/document/d/1ekuqpFijy7uXWKH51KyPX41jKc_1COwepbzOCXzOaEc)


#### Unit 4: ChatBot Aid

![ChatBot Answer to a Question]({{ site.baseurl }}/assets/independent_study/chatbot_answer.png)

This unit is the first one where students are specifically instructed to use a
ChatBot to help create something that they might otherwise struggle to complete
on their own. The point of this unit, as with the other, future units, is to
get students comfortable with using a ChatBot to augment their abilities while
simultaneously forcing them to reflect/understand the code that is being created.

In particular, this unit has students create a series of GitHub Pages websites
of increasing complexity. The final, most difficult one is a "spinner" that I
can use in my other classes to pick an in-class participant. The goal is for
them to see the web as a series of HTML/JavaScript websites with various API
back-ends.

##### Keywords

ChatBots, GitHub, HTML, JavaScript, APIs, Client-side Apps

##### Resources

- [Hello GitHub Worksheet](https://docs.google.com/document/d/1wLQTRCPJ1zliQjcpnfUkqjNVW4aJ8giYrCCRPT3QLUA)
- [ChatBot Roulette Worksheet](https://docs.google.com/document/d/1PDXcbG9Ae8Hniw7MvHyTZVbjTzZmpKXqeun8eJP_iTs)
- [Modern Web Apps Worksheet](https://docs.google.com/document/d/1yYhvBxneYn3HMrBUWB0riLzorkQRII0tinSizXNh6cY)

#### Unit 5: AWS Dev Part 1

![AWS Lambda logo]({{ site.baseurl }}/assets/independent_study/aws_services.png)

This unit has students start to create a (very simple) backend API for the
websites they created in the previous unit. It guides them through the usage and
creation of basic AWS components such as a simple Lambda (compute), DynamoDB
table (memory), and S3 bucket (storage). Once they understand each of these
individual parts, they tie them together to create their first AWS based
service.

Getting up to speed on this can be fairly difficult, so the worksheets are
designed to prompt students to both use a ChatBot **and** consider the output
being produced by the ChatBot. The goal is for students to come to understand
that AWS is simply a wrapper for their code that allows it to be easily run/
scaled on the internet.

##### Keywords

Lambda, Regions, DynamoDB, S3, Permissions, boto3

##### Resources

- [AWS Intro Worksheet](https://docs.google.com/document/d/1k9zt-XQJZDGlWAC87l09PZ_GT9oc8sGcIeKrBFq6sAg)
- [DynamoDB Intro Worksheet](https://docs.google.com/document/d/1N5vOdbItnN81a0iwexD3kV5n7kvP6bbS7h5THOxMUqM)
- [S3 Intro Worksheet](https://docs.google.com/document/d/1WwM4kJjMKh41zh4sN1tGyI0cAWhffMAP7I7Ur8_s-hM)

#### Unit 6: Docker

![Docker Logo]({{ site.baseurl }}/assets/independent_study/docker.png)

Docker is a fundamental technology of the modern web. Understanding how it
works, even at a high level, helps students appreciate how code moves around
the globe. In this unit, students learn to run, augment, and build Docker their
own containers. A particular highlight is that they get to look at the image I
use for my middle schoolers: the "Harry Potter Terminal Scavenger Hunt".

In the end, students will have an appreciation for how code can be containerized
and therefore understand how their code (in a Docker image) can interface with
the services that AWS provides.

##### Keywords

Containers, DockerHub, Lambda, Environment, Program Hooks, Serverless, Harry Potter

##### Resources

- [Docker Intro Worksheet](https://docs.google.com/document/d/1BXl2eWHTXz2hGJeljlIaKgKq84DUOPS7wvJAcuiL_p0)
- [Serverless Docker Worksheet](https://docs.google.com/document/d/1uz90cVLRvoGtuCpYqWeNYBw4waXxQW4OEyGHA4HOmgU)

#### Unit 7: AWS Dev Part 2

![GitLab Pipeline]({{ site.baseurl }}/assets/independent_study/gitlab_pipeline.png)

In the penultimate portion of the independent study, students learn to build
and deploy their code using two pipelines: a source code pipeline and an
infrastructure pipeline. Once they are able to deploy, they learn how (and why)
to add a lot of software engineering best-practices such as a dashboards and
integration tests.

In the end, students can deploy a simple Lambda based service that stores
information in both S3 and DynamoDB and can be called via the internet using API
Gateway. As a final "cherry on top", they then replace the API call they made in
their GitHub Pages website to a call to their own API.

##### Keywords

CI/CD, Dashboards, Integration Testing, Infrastructure vs. Code, CDK

##### Resources

- [Infra as Code Worksheet](https://docs.google.com/document/d/1ZLFzG_-HqCs_UDjQs9KIOmp8zFPp5bSBtSDVgH_3e34)
- [API Gateway Intro Worksheet](https://docs.google.com/document/d/1exAsqMfjrSYUT08oBmxrDCngnI5ldqXDq81y6yvncgQ)
- [Src Deployment 1 Worksheet](https://docs.google.com/document/d/15mgQNYt54nPrwl8miEN0n_T1ZJqVGHRXdm3BB0animg)
- [Src Deployment 2 Worksheet](https://docs.google.com/document/d/1-gtga6QumvTnGSImP2Noo9279mJ0FdsR8_D1jwYiU2s) - PENDING
- [Dashboard Worksheet](https://docs.google.com/document/d/1XYs5yg7N-iALpGJISFtZOZ4GmgHvgZPV1EADaSWCjDg) - PENDING
- [Integ Test Worksheet](https://docs.google.com/document/d/1R_LksGNqv2zxR_O1FiwlW-26vI7MWVc99F_Je2SV7ts) - PENDING
- [AWS Infra Repository](https://gitlab.com/eric.rizzi/aws-infra-txu.git)
- [AWS Src Repository](https://gitlab.com/eric.rizzi/aws-src-txu.git)

#### Unit 8: Proof of Knowledge

In this final unit, students are asked to design a system that will solve a
problem for someone in the school. They will have to talk to teachers/staff,
create a plan, get buy-in from the interested parties, and finally build the
actual project. Possible projects include: a game for a lower school class,
a tool for librarians to track books, or a 3D printer utility for the science
department.

In the end, students will be assessed on how much their project satisfies the
original vision **and** how much their solution relies on the concepts they
learned throughout the course. Finally, students will have to give a high-level
presentation on the design of their system and the choices they made along the
way. The presentation will be targeted at people who have _some_ programming
knowledge, but are not experts in AWS/distributed systems. This will require
students to solidify their knowledge and abstract it so other students learn
about what is possible.

##### Keywords

Final Project, Specifications, Creativity, Best-Practices

##### Resources

- PENDING
