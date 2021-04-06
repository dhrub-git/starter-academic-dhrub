---
title: DevOps Capabilities Assessment
subtitle: DevOps transformation, or simply evaluating the capabilities required
  to accelerate your company’s delivery and quality performance, these are the
  questions you should ask yourself.
date: 2021-04-04T06:45:30.442Z
summary: DevOps transformation, or simply evaluating the capabilities required
  to accelerate your company’s delivery and quality performance, these are the
  questions you should ask yourself.
draft: false
featured: false
tags:
  - DevOps
  - AWS
  - Azure
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
<!--StartFragment-->

# DevOps Capabilities Assessment



<!--EndFragment-->

<!--StartFragment-->

Whether you are starting a new company or going through a DevOps transformation, or simply evaluating the capabilities required to accelerate your company’s delivery and quality performance, these are the questions you should ask yourself.

The right answer to all these questions is always yes, if it’s no for your company you should look if it applies to your organisation or if you can improve or implement it. You could also rate the questions in a scale 1 to 7 and then add up your results at the end, because sometimes answers don’t come in binary ;-)

Most of these questions come from reading the [Accelerate book](https://medium.com/@nandovillalba/accelerate-digest-c04c7f6ba044) by Nicole Forsgren, Jez Humble and Gene Kim and from their [survey questions](https://blog.newrelic.com/technology/dora-accelerate-state-of-devops-survey/) for State of DevOps.

The list is not exhaustive but it is as comprehensive I could make it, I aimed to separate the questions in capabilities, following the model outlined in their book the best I could.

I will update this blog post with more questions as I learn more. If you stumble upon this post and want to contribute, feel free to comment with your own too and I will add them in if I feel they substantially improve the post.

# Continuous Delivery Capabilities

## Version Control

Is your code in version control?

Is your configuration management in version control?

Are you doing infrastructure as code?

## Deployment Automation

How quickly fix issue?

Does your CI/CD toolchain includes the following?:

[Automated build](https://en.wikipedia.org/wiki/Build_automation)

[Automated unit tests](http://softwaretestingfundamentals.com/unit-testing/)

[Automated acceptance tests](https://www.infoq.com/news/2017/04/acceptance-testing-delivery)

[Automated performance tests](https://www.neotys.com/documents/whitepapers/whitepaper_agile_load_testing_en.pdf)

[Automated security tests](https://medium.com/@cossacklabs/automated-security-testing-56ee1253c1fd)

[Automated provisioning and deployment of testing environments](https://www.capgemini.com/2017/02/automated-test-environments-for-devops/)

[Automated deployment to production](https://www.atlassian.com/continuous-delivery/continuous-deployment)

[Integration with chatbots/slack](https://chatbotsmagazine.com/how-chatops-can-help-you-devops-better-5-minutes-read-507438c156bf)

[Integration with production monitoring and observability tools](https://medium.com/@copyconstruct/monitoring-and-observability-8417d1952e1c)

## Continuous Integration

Do your code commits result in automated build of the software?

Do code commits result in automated tests being done?

Does your company pass this test?:

![](https://miro.medium.com/max/60/0*3H9ZUQmep7t5M8WR.png?q=20)

![](https://miro.medium.com/max/840/0*3H9ZUQmep7t5M8WR.png)

> Note: Effective CI is largely dependent on Trunk Based Development, deployment automation, test automation, test data management and version control capabilities.

## Trunk Based Development

Are there less than three active long lived branches in your repositories?

Do all developers merge to trunk at least daily?

Could you say with certainty that you never have code locks? (Periods where no one can merge to master until release is done.)

Are branches and forks short lived before being merged to master often?

## Test Automation

When automated tests pass, are you confident your software is reliable?

Are the vast majority of your automated test failures likely to indicate a real defect?

is it easy for developers to reproduce and fix test acceptance failures?

Can you get feedback from automated tests in less than ten minutes?

Do you regularly use data from previous test runs to improve the quality of test suite?

Do developers create and maintain their own automated tests?

Do QA teams assist and help design an automated suite of tests with your developers?

Do developers do Test Driven Development wherever feasible?

## Test Data Management

Do you have the test data necessary to run automated tests easily at every run without the need to copy and use production data?

## Shift Left on Security

Is security betted and checked before and during development?

Do you have automated security tests as part of your software delivery cycle?

Do you regularly communicate and keep infosec on the loop so they can assess and advice on the ongoing development process?

## Continuous Delivery

Is your trunk always in a deployable state?

Does your team prioritises maintaining deployable state over working on new features?

Is fast feedback available to all teams of the state of the trunk and deployments?

When your team gets feedback that system is not deployable, do they make it a priority to fix it immediately?

Can you deploy any time to production on demand with a high degree of confidence?

> Note: Effective CD is largely dependent on effectively implementing your CI capability.

# Architecture Capabilities

## Loosely Coupled Architecture

Can you make changes without depending or coordinating with other teams?

Can you make changes without affecting other teams?

Can you do most of the testing without requiring integrated testing environment?

Can you perform deployments during normal business hours?

Can you do all of the above without requiring permission from top management or other teams?

## Empowered Teams

Do your teams have leeway to pick their own tools? (This of course applies to anything that doesn’t need to be centralised, you often wouldn’t want every team with a different container orchestrator)

Can you release a product or service on demand?

Do you have a CI/CD toolchain that’s useful and increases your productivity?

Is your CI/CD toolchain easy to understand and use?

Do you find that it is easy to implement changes in your CI/CD tool chain for it to do what you want?

Do teams get to choose their own CI/CD toolchain?

Do teams have complete autonomy over the CI/CD toolchain?

Are teams focusing on outcomes rather than on shiny new tools?

Do you deploy during normal business hours?

# Product and Process Capabilities

## Customer Feedback

Do you actively seek customer feedback and incorporate it into the workflow and design of your product?

## Value Stream

Do you have a good visibility of the workflow from business to customer, including metrics and status?

Do your teams design and deliver work to cater to the next step in the value stream? (This basically means that you don’t just chuck work that only you understand to someone else to figure it out and even patch it to make it work for them)

Is it easy to reuse other people’s code?

Is it easy to add dependencies to a project?

Are your dependencies stable and rarely break the code?

## Working in Small Batches

Can you effectively slice your work in small batches and allocate it to various members of the team?

Can these batches be treated as a unit or MVP to be deployed?

## Team Experimentation

Is it safe for your team to take reasonable risks?

Do you provide environment where your teams can be innovative?

Do your teams have the authority to create and change specifications as part of the development process without requiring approval?

> Team experimentation should be paired with working in small batches, making the flow work visible to everyone and incorporating customer feedback into the design of products. This is to ensure that teams make well-informed choices about the design, development and delivery of work. This also ensures that their decisions are communicated to everyone in the organisation.

# Lean Management and Monitoring Capabilities

## Change Approval Processes

Can your changes be approved for release within the team?

Can your low risk changes be released with confidence straight away after a set of automated tests has been performed only requiring manual approval for high risk changes?

Are you confident you can get changes on production in a timely manner?

Are the steps to release well known, documented and easy to follow?

Can you deploy significant changes without approval of top management?

Can you do releases without approval or coordination with other teams?

## Monitoring

Can you view the overall health of the system at any given point with alerts in place?

Do you have a tech solution to report the system state to customers in place?

Do you have a solution to report key business and system metrics?

Do you have system in place to help you debug and understand production systems quickly and effectively?

## Proactive Notification

Do you have well defined targets for availability (SLA/[SLO](https://landing.google.com/sre/sre-book/chapters/service-level-objectives/)) that are communicated among teams?

Do you know what the availability was in a recent period?

Did you exceed SLO for a target period?

When you miss a SLOs do you reprioritise and perform improvement work?

## WIP Limits

Do your teams have limits for the amount of work they are working on any given time?

Do you focus on quality and relevant features rather than quantity?

## Visualising Work

Do your teams always have a way to easily visualise the work that is being done or planned to do at any given moment? (For example with a kanban board)

Do they have a way to view the results and effects of their work with visualisation and observability?

# Cultural Capabilities

## Westrum Organizational Culture

Do your company fall under the generative column in the following table?:

![](https://miro.medium.com/proxy/0*JgP8VEm64tsm0ho1.png)

Are the teams in your organisation like this?:

![](https://miro.medium.com/proxy/0*T_iEOG6vgFUus4Uw)

## Supporting Learning

Am I able to get all the information I need to do my job effectively? (For example strategy, new products, organisational changes, priorities and values)

Do you have a training budget?

Do employees have the resources and space to explore ideas an engage in informal learning? (For example a cloud platform to goof around and spin test environments, etc)

Do you conduct blameless postmortems where you learn and get action items from?

Do you have spaces where people can share information effectively?

Do you conduct demo days and forums for discussions?

Do you encourage staff to attend technical conferences at least once a year and summarise what they learned for the entire team?

Do you setup internal hack days, where cross-functional teams can get together to work on a project?

Do you encourage teams to organise internal “yak days” to address technical debt?

Do you hold internal DevOps mini-conferences where the various teams can learn from each other?

Do you give staff dedicated time and budget to experiment with new tools and technologies?

Is your code visible by all teams?

Can you edit code by other teams?

Does the team have clear roles and responsibilities?

Are your team members opinions valued?

Can you find answer to most common problems in an internal wiki without having to google for it?

## Job Satisfaction

Are projects personally meaningful to most employees?

Do they have a chance to make good use of skills and abilities?

Are they intellectually challenged?

## Transformational Leadership

The following five areas cover transformational leadership, ask these questions about your leaders to find out if they are transformational:

**Vision**

* Do they have a clear understanding of there we are going?
* Do they have a clear sense of where he wants the team to be in five years?
* Do they have a clear idea of where the organisation is going?

**Inspirational Communication**

* Do they say things that make employees proud to be part of the organisation?
* Do they say positive things about the work unit?
* Do they encourage people to see changing environments as situations full of opportunities?

**Intellectual Stimulation**

* Do they challenge me to think about old problems in new ways?
* Do they have ideas that force me to rethink some things that I have never questioned before?
* Have they challenged me to rethink some of my basic assumptions about my work?

**Supportive Leadership**

* Do they consider my personal feelings before acting?
* Do they behave in a manner which is thoughtful of my personal needs?
* Do they see the interests of employees are given due consideration?

**Personal Recognition**

* Do they commend me when I do a better than average job?
* Do they acknowledge improvement in my quality of work?
* Do they personally compliment me when I do outstanding work?

# Chaos Engineering

Do you have infrastructure and database failover in place?

Application failover?

Simulations that disrupt production like systems? (Including failure injection such as degrading network links, turning off routers, etc.)

Ditto but in production?

Do you utilise something like [chaos monkey](https://github.com/Netflix/SimianArmy/wiki/Chaos-Monkey)?

Do you ever do t[able top exercises](https://medium.com/@paulcichonski/tabletop-exercises-for-engineering-teams-a7a851b39c79)?

Are the above carried out regularly and fairly often?

Do action items to address the issues encountered come from the tests and are fixed?

# Additional Info

<https://cloudplatformonline.com/rs/248-TPC-286/images/DORA-State%20of%20DevOps.pdf>

<https://devops-research.com/assets/transformation_practices.pdf>

<!--EndFragment-->