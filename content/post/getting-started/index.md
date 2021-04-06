---
title: AWS Solution Architect Exam Tips
subtitle: Tips to understand the details for the AWS Solution Architect Exams
  and post exam practices
date: 2020-12-13T00:00:00.000Z
summary: Welcome 👋 We know that first impressions are important, so we've
  populated your new site with some initial content to help you get familiar
  with everything in no time.
draft: false
featured: false
authors:
  - dhrub
lastmod: 2020-12-13T00:00:00.000Z
tags:
  - AWS
  - SolArc
categories:
  - AWS
projects: []
image:
  caption: ""
  focal_point: ""
  placement: 2
  preview_only: false
  filename: featured.jpg
---
<!--StartFragment-->

# Exam Preparation

* *If you don’t have any experience with AWS service, I will recommend first start with acloudguru.com. Please don’t miss **AWS — 10,000 Foot Overview,** this will give you a good overview of all the AWS Services.*

<!--EndFragment-->

<!--StartFragment-->

* *The second, one of the most useful resource is Linux Academy. One of the advantages of using Linux Academy is its hands-on lab. This will give you enough hand’s on experience required for the certification.*


* ***AWS Re: Invent Videos:** I highly recommend going through these videos, as they will give you enough in-depth knowledge about each service.*
* ***AWS Documentation:** Best documentation ever provided by any service provider. Don’t miss the FAQ regarding each service(especially for EC2, S3, VPC)*
* Exam Readiness
* *Last but not the least, hands-on experience, there is no substitute for that. As per certification pre-requisite*

![](https://miro.medium.com/max/60/1*n_viEu5dPF9BxmTykGQmZw.png?q=20)

![](https://miro.medium.com/max/1652/1*n_viEu5dPF9BxmTykGQmZw.png)



## Services

*You must know these three services in order to clear this EXAM*

* *EC2*
* *VPC*
* *S3*

*Some services which I under-estimate and I saw at least 2–4 question related to those services*

* *DynamoDB*
* *Kinesis Firehouse*
* *CloudFront*
* *SQS*

*I am not using any of these services in my day to day operation, and that’s why I didn’t pay much attention. Also, it’s time for AcloudGuru and Linux Academy to add some more in-depth content related to these services*

***Some surprise packages***

* *AWS Athena*
* *AWS Inspector*

***My Idea about the exam***

* *As this is an associate level exam, my initial perception about this exam that I don’t need to go in-depth of all of the services but this exam surprises me with some in-depth questions. So please make sure to read/implement as much as possible about (EC2/VPC/S3).*

## Let’s talk about different Services and what concept you should know in order to clear this exam

## S3

* *This table is the key to understand different S3 storage classes. Make sure you understand*

```

```


## [Cloud Storage Classes — Amazon Simple Storage Service (S3) — AWS](https://aws.amazon.com/s3/storage-classes/)

### [Explore S3 cloud storage offerings for different durability and availability levels, including Amazon S3 Standard, S3…](https://aws.amazon.com/s3/storage-classes/)

[aws.amazon.com](https://aws.amazon.com/s3/storage-classes/)

* *Understand S3 Object Lifecycle Management and when to move an object to S3-Standard-IA/S3 One Zone IA vs Glacier*

## [Object Lifecycle Management — Amazon Simple Storage Service](https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html)

### [Use Amazon S3 to manage your objects so that they are stored cost effectively throughout their lifecycle.](https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html)

[docs.aws.amazon.com](https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html)

* *Difference between Server access logging vs Object Access logging*

## [Serve access logging vs Object-level logging](https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-L5KnjS2mlyqPvuMu00f/Serve%20access%20logging%20vs%20Object-level%20logging)

### [Currently after creating my S3 buckets under properties, I see Server access logging and object-level logging. What is…](https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-L5KnjS2mlyqPvuMu00f/Serve%20access%20logging%20vs%20Object-level%20logging)

[acloud.guru](https://acloud.guru/forums/aws-certified-solutions-architect-associate/discussion/-L5KnjS2mlyqPvuMu00f/Serve%20access%20logging%20vs%20Object-level%20logging)

* *Understand how encryption(both Server/Client) works for S3*

## [Protecting Data Using Encryption — Amazon Simple Storage Service](https://docs.aws.amazon.com/AmazonS3/latest/dev/UsingEncryption.html)

### [Use data encryption to provide added security for your data objects stored in your buckets.](https://docs.aws.amazon.com/AmazonS3/latest/dev/UsingEncryption.html)

[docs.aws.amazon.com](https://docs.aws.amazon.com/AmazonS3/latest/dev/UsingEncryption.html)

* *Cross region replication in S3*

## [Cross-Region Replication — Amazon Simple Storage Service](https://docs.aws.amazon.com/AmazonS3/latest/dev/crr.html)

### [Set up and configure cross-region replication to allow automatic, asynchronous copying of objects across Amazon S3…](https://docs.aws.amazon.com/AmazonS3/latest/dev/crr.html)

[docs.aws.amazon.com](https://docs.aws.amazon.com/AmazonS3/latest/dev/crr.html)

* *Surprise package **Amazon S3 inventory***

## [Amazon S3 Inventory — Amazon Simple Storage Service](https://docs.aws.amazon.com/AmazonS3/latest/dev/storage-inventory.html)

### [Describes Amazon S3 inventory and how to use it.](https://docs.aws.amazon.com/AmazonS3/latest/dev/storage-inventory.html)

[docs.aws.amazon.com](https://docs.aws.amazon.com/AmazonS3/latest/dev/storage-inventory.html)

```

```

## AWS Storage Gateway

* *Difference between different storage gateway and which one to use under which situation(Especially when they ask migrating services from on-premises data center to AWS cloud and how to keep data in sync)*

## [What Is AWS Storage Gateway? — AWS Storage Gateway](https://docs.aws.amazon.com/storagegateway/latest/userguide/WhatIsStorageGateway.html)

### [Find an introduction to AWS Storage Gateway, which connects your on-premises environment with cloud-based storage.](https://docs.aws.amazon.com/storagegateway/latest/userguide/WhatIsStorageGateway.html)

[docs.aws.amazon.com](https://docs.aws.amazon.com/storagegateway/latest/userguide/WhatIsStorageGateway.html)

## AWS Snowball

* *Whenever they ask about Petabyte(even terabyte) this is the best bet(Again migrating on-premises data center to AWS)*

# EC2

* *Understand the difference between different purchasing options(On-demand, Reserved, Spot and Dedicated)*

## [Instance Purchasing Options — Amazon Elastic Compute Cloud](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-purchasing-options.html)

### [Amazon EC2 provides different purchasing options that enable you to optimize your costs.](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-purchasing-options.html)

[docs.aws.amazon.com](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-purchasing-options.html)

* *Pay special emphasis to Dedicated Hosts(Look for Keyword like **compliance requirements /server-bound software licenses**)*
* *Understand the difference between Instance Store Volumes vs EBS(Look for Keyword shutdown as in case of Instance Store Volumes your data will be Wiped)*

## [Understand the Instance Store and EBS](https://aws.amazon.com/premiumsupport/knowledge-center/instance-store-vs-ebs/)

### [For data you want to retain longer, or if you want to encrypt the data, use Amazon Elastic Block Store (Amazon EBS)…](https://aws.amazon.com/premiumsupport/knowledge-center/instance-store-vs-ebs/)

[aws.amazon.com](https://aws.amazon.com/premiumsupport/knowledge-center/instance-store-vs-ebs/)

* ***Security Group**(They are not going to ask you this question directly but mostly scenario based questions like multi-tier environment where you have web frontend vs MySQL as database and which port you are going to open in your backend DB(MySQL), As you only need a connection from the web frontend, you only need to specify Mysql DB security group)*

## LoadBalancer

* *Difference between Application vs Network Load Balancer and in which scenario you are going to use which one*

## [Elastic Load Balancing Features](https://aws.amazon.com/elasticloadbalancing/features/)

### [Elastic Load Balancing provides integrated certificate management and SSL/TLS decryption, allowing you the flexibility…](https://aws.amazon.com/elasticloadbalancing/features/)

[aws.amazon.com](https://aws.amazon.com/elasticloadbalancing/features/)

# VPC

* *Create VPC from scratch(At least 2 Private Subnet and 2 public Subnet)*
* *What is the use of Internet Gateway and what changes you need to make in your routing table to route the traffic to the internet(0.0.0.0/0 to IGW)*
* *How Private Instance is going to talk to the Internet(NAT Gateway)(again create it from scratch)*
* *VPC Endpoints(understand the difference between Gateway Endpoint vs Interface Endpoint)*
* *Difference between NACL vs Security Group*

## CloudWatch

* *Remember Cloudwatch now is not only to display metrics but you can also push application logs via Cloudwatch agents*


## [What is Amazon CloudWatch Logs? — Amazon CloudWatch Logs](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html)

### [Describes the fundamentals, concepts, and terminology you need to know for using CloudWatch Logs to monitor, store, and…](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html)

[docs.aws.amazon.com](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html)

* ***Placement Group:** Justbrief idea about EC2 Placement group and what is the purpose of it(keyword low latency between ec2 instances)*

## [Placement Groups — Amazon Elastic Compute Cloud](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/placement-groups.html)

### [Launch instances in a placement group to cluster them logically into a low-latency group, or to spread them across…](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/placement-groups.html)

[docs.aws.amazon.com](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/placement-groups.html)

* ***Elastic File System(EFS)**: Look for a key term like the instance need to be **simultaneously mounted** on the bunch of EC2 instances(Choice between S3/EBS/EFS)*

## [Amazon Elastic File System (Amazon EFS) — Amazon Elastic Compute Cloud](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEFS.html)

### [Use Amazon EFS to create an EFS file system and mount it to one or more of your Linux instances.](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEFS.html)

[docs.aws.amazon.com](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEFS.html)

* ***Lambda:** Whenever they talk about cost optimization then lambda is your go-to choice(But please read the scenario carefully)*

# Route53

* *Understand the difference between different routing policy*

## [Choosing a Routing Policy — Amazon Route 53](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html)

### [Choose a routing policy before you create records in Amazon Route 53.](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html)

[docs.aws.amazon.com](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html)

* *Pay special emphasis to a latency based(key word user in specific region facing latency, so key choice is between Route53 vs CloudFront)and failover routing policy*

***Autoscaling:** Just a brief idea about how auto-scaling works*

# Databases

* *For RDS MySQL understand the difference between read-only replication(performance gain) vs HA(in case of failover)*
* *AWS is paying special emphasis on Aurora, so in case if they ask migrating on-premises MySql/Postgres to AWS Cloud then Aurora is the best bet*

***IAM***

* *Make sure you understand the purpose of roles and use roles to communicate to different AWS Service, rather than using Public Internet Route*



<!--EndFragment-->
