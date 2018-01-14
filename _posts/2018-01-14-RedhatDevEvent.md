---
layout: post
title: "Red Hat Dev Event: IT modernization through automation"
description: "The principle of Hero As Code and Network Automation"
headline:
modified: 2018-01-14 14:15:00 +0530
category: personal
tags: []
feature-img:
mathjax:
chart:
author: 'Divyansh Kulshreshtha'
comments: true
featured: true
---

# Introduction
The webinar was on held on January 12th 2018 and was on the topic **Automation for network infrastructures**, it was hosted by Gerald Dykeman who works as a Domain Architect at Ansible. The webinar was mainly focused on the principle of Hero As Code and why we need a proper network automation system and how Ansible helps us in achieving that.

## What is Hero As Code?
So, let’s imagine a person, say Bob. Bob is the one who designs, builds, fixes and maintains the network all on his own. So Bob is the **Hero** for us. But, Heroes are in high demand, Bob knows a lot and can work on any project, but the problem with this is Bob is called everywhere! He is not able to manage so many clients together. So here comes the principle of Hero As Code, in this theoretically, Bob and the entire infrastructure is converted into code. All of his basic (and some complex) functions are written into the codebase. This is somewhat what serves as the base of network automation.


## The Primitive Network Structures
We are in 2018, and people still configure VLANs on their respective networks manually, people are still hesitant to go towards the route of automation because they are mostly worried that the process might go down at any point of time and then there won’t be any human power to handle those errors.
In primitive network structures, the team or individual maintaining it is usually the main component. This methodology is not exactly fool proof as there can be a number of human error and sometimes even a small mistake can cause the entire network to go down. 


## Why automation?
So this takes us to the very important question, Why automation of networks? How is it any beneficial from what we are using now?
So, few of the advantages of network automation are: 
Backups and restore can be easily automated.
Ensures proper working of networks without or hardly any use of manpower. 
The process of  Plan → Develop → Test → Deploy → Operate can be executed a lot faster. 


## What is Ansible
So, **Ansible** is basically a software company owned by Red Hat Inc.  that automates provisioning, configuration management, and application deployment. Ansible makes it easy to scale automation, manage complex deployments and thus it increases the overall productivity of the project.


## Why Ansible?
The next question that may arise in your mind is why Ansible? So, Ansible is simple, no special coding skills are required to work with it, it’s very powerful, and is very secure. Currently it supports 33 networking platforms and over 460+ networking modules (modules from Cisco, Juniper. Dell and many more!)
Ansible works via small individual modules and these can be used according to the requirements for example the cisco module can be used only for some parts of the network and the rest can be configured automatically, Most of the configuration is done in the **yaml** file. The Ansible tower supports different APIs . The tower takes in the API calls and configures the server accordingly. 
It also has integrations with popular services like Splunk, VMware, Atlassian, Gitlab and almost all of Red Hat products.


## Questions Raised

**Q.1 Why is automation the prefered way in the future?**

Ans. Network automation should be preferred because it has several benefits for the user, its helps reduce the workload as, you are still doing the same stuff that you were doing earlier, but now you can repeat that and iterate on that. This makes the whole process efficient. 


**Q.2 How is the principle of Hero as code and Ansible going to affect the network engineers?**

Ans, The engineers have problems in scaling, for every fault that occurs, it is not possible for the administrator to go and fix them. Basically, if there is something that you repeat, should be automated and Ansible does just that, it kicks away the manual tasks and allows you to do things that matter to your business.


## My Experience
This was my first professional developer webinar.I was confused about how this event would turn out for me as although I was familiar with network architectures, automation and related terminologies, I did not have a deep knowledge of any of them but the webinar was very well organised and the speaker explained each and every topic beautifully. It introduced me to network automation and how it will be beneficial for everyone in the future. I got to know about Ansible and how it would help us reach almost complete automation of our network infrastructures.  
