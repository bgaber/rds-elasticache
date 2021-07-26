# Show me the money ... the cash ... the cache
![Alt text](readme_images/diagram-CGC-june-july-2021.jfif?raw=true "Improve application performance using Amazon ElastiCache")

Goal
----
The goal of this project is to observe a signicant improvement in the performance of a web application by implementing a Redis cluster using Amazon ElastiCache to cache database queries in a simple Python application.

Project Description
-------------------
This project has two main steps.  First, implement a LAMP style web application using Linux, NGINX, PostGreSQL and Python.  Measure the performance of a Python application that is intentionalyy made slow.  Second, add an Redis ElastiCache to the web application and observe the improvement in performance.

Main Steps
----------
1. Using CloudFormation, create a LAMP style web application using Linux, NGINX, PostGreSQL and Python.  This Cloudformation template is found in the github repository.

2. Measure the performance using an Instance in the EU-West-1 (Ireland) region.

3. Using CloudFormation, add an Redis ElastiCache to the web application.  This Cloudformation template is found in the github repository.

4. Measure the performance a second time using the same Instance in the EU-West-1 (Ireland) region.

Implemented Architecture
------------------------
The diagram below depicts the architecture I implemented.  The entire architecture was created by two CloudFormation templates.
![Alt text](readme_images/rds-elasticache.png?raw=true "RDS ElastiCache Architecture")

References
----------
#CloudGuruChallenge: Improve application performance using Amazon ElastiCache - https://acloudguru.com/blog/engineering/cloudguruchallenge-improve-application-performance-using-amazon-elasticache

Lab: Using ElastiCache to Improve Database Performance - https://acloudguru.com/hands-on-labs/using-elasticache-to-improve-database-performance
