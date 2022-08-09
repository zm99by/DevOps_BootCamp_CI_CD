#  DevOps BootCamp: CI/CD

## Day 0: Continuous integration vs. delivery vs. deployment

### Continuous integration

```
Developers practicing continuous integration merge their changes back to the main branch as often as possible. 
The developer's changes are validated by creating a build and running automated tests against the build. 
By doing so, you avoid integration challenges that can happen when waiting for release day to merge changes into 
the release branch.

Continuous integration puts a great emphasis on testing automation to check that the application is not broken 
whenever new commits are integrated into the main branch

```

### Continuous delivery
```
Continuous delivery is an extension of continuous integration since it automatically deploys all code changes to 
a testing and/or production environment after the build stage. 

This means that on top of automated testing, you have an automated release process and you can deploy your application 
any time by clicking a button.

In theory, with continuous delivery, you can decide to release daily, weekly, fortnightly, or whatever suits your 
businessrequirements. However, if you truly want to get the benefits of continuous delivery, you should deploy 
to production as early as possible to make sure hat you release small batches that are easy to troubleshoot in
case of a problem.
```

### Continuous deployment

```
Continuous deployment goes one step further than continuous delivery. With this practice, every change that passes
all stages of your production pipeline is released to your customers. There's no human intervention, and only a 
failed test will prevent a new change to be deployed to production.

Continuous deployment is an excellent way to accelerate the feedback loop with your customers and take pressure 
off the team as there isn't a "release day" anymore. Developers can focus on building software, and they see their 
work go live minutes after they've finished working on it.
```

                **How the practices relate to each other:** <br>
To put it simply continuous integration is part of both continuous delivery and continuous deployment.
And continuous deployment is like continuous delivery, except that releases happen automatically.
![alt text](https://github.com/zm99by/DevOps_BootCamp_CI_CD/blob/main/pic.png?raw=true)


## Day 1: Continuous Integration with Jenkins
### ***Description***

```
The course describes the continuous integration and delivery processes. 
Practical part shows how to setup the Jenkins based CI from scratch.
The goal of this course is to learn how continuous integration and delivery processes work.
```

https://learn.epam.com/detailsPage?id=59bdf234-6664-4f38-a9c5-6689edd6f8d4

## Day 2: Jenkins Fundamentals
### ***Description***

```
In this course, we will cover the fundamentals of Jenkins, including continuous integration/continuous delivery (CI/CD) 
and continuous deployment. After that, we will move on to installing and configuring Jenkins, and get familiar with the 
graphical user interface. We will explore jobs and builds as well as build agents. This will give us the foundation we 
need to accomplish more complex Jenkins tasks.
```

**https://learn.acloud.guru/course/e81aa3d0-bd3e-4a49-9bf8-dc4412e74f6c/overview**

## Day 3: Jenkins by Doing
### ***Description***

```
You learn faster and better when you learn by doing. With that in mind, this course has been designed to allow 
you to practice core Jenkins Builds through a 100% hands-on experience. To accomplish this, Linux Academy's Training 
Architects have hand-selected a set of the best Jenkins hands-on labs we have to offer.

Everything in this course will be on one or more Linux servers provisioned with whatever needed through our hands-on lab 
and Cloud Playground platform.

There's no reason to wait; learn by doing today!
```

**link: https://learn.acloud.guru/course/03c036a0-ef8c-41a0-bc5f-0ce9c0b29000/dashboard**


