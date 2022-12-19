# AWS Infrastructure

![](/home/david/WebstormProjects/nd0067-c4-deployment-process-project-starter/assets/awsDiagram.png)

## RDS

RDS is AWS's relational database service. It handles the app data
* configure for postgres
* t3.micro is sufficient

## S3

S3 is AWS's storage service for media and other objects
* enable static website hosting
* open bucket to public

## Elastic Beanstalk
Eb is AWS's service to simply host and scale web applications
* t2.medium is sufficient
* eb config file in project will configure the instance
* integrate environment variables into eb env
