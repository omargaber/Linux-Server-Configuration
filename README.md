# Linux Server Configuration Project
Source code for a Log Analysis Project.
By Omar Gaber Abdelmaksoud.

This is the **sixth** project made for fulfillment of [Udacity's Full Stack Web Development Nanodegree Program](https://www.udacity.com/course/full-stack-web-developer-nanodegree--nd004)

## Abstract
The project's main focus was to put to test, the fundamental knowledge and operations of deploying the item catalog application whilst configuring the linux server on which it will be hosted, taking into consideration security measures and user privilages. 


* **IP Address** 35.177.214.12.

* **SSH Port** 2200.

* **URL:** http://ec2-35-177-214-12.eu-west-2.compute.amazonaws.com/ .

* **SSH Key Location** `/home/grader/.ssh/authorized_keys`

## Software installed
* All dependencies of the Item Catalog App, that includes Flask, OAuth2, PostgreSQL etc.

* Configured the ufw to allow ssh access through port 2200, enable http get requests (port 80), and enable ntp requests through port 123.

* Created user `grader` to which sudo access was given.

* Configured Apache2 service.

* Installed tzdata to configure timing to UTC.


## Third Party Resources made use of to complete this project
* [DigitalOcean Walkthrough](https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps)
