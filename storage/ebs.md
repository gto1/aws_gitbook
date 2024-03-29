---
description: Elastic Block Store
---

# EBS

EBS (Elastic Block Store) and [S3](untitled.md) are two storage services provided by Amazon. The main difference between them is with what services they can be used. EBS is specifically meant for [EC2](../servers/ec2.md) (Elastic Computing Cloud) instances and is not accessible unless mounted to one.

![Amazon EBS (aws.training)](<../.gitbook/assets/Screen Shot 2019-10-26 at 3.27.42 PM.png>)

## Durability and Backup

* Automatic replication within it's Availability Zone (AZ)
* Incremental snapshot back-up to Amazon S3 (optional)

## I/O Provisioning

* Provision a specific level of I/O performance
* Or select a _burstable_ performance model
* Scale to tens of thousands of IOPS per EC2 instance

## Types of EBS Volumes

* Standard
* Provisioned IOPS
* General Purpose

![EBS types (aws.training)](<../.gitbook/assets/Screen Shot 2019-10-26 at 3.58.08 PM.png>)

