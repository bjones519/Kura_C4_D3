# Kura_C4_D3

## Purpose
- Deploy a web application in a fully automated Elastic Beanstalk Environment using Jenkins

## Issues
- When installing the aws eb cli as the jenkins user I was prompted that I needed to install python3-pip and I couldnt do it as the jenins user, I had to logout and install as the ubuntu user and then it worked
 ![AWS](AWSError.jpg)

## Steps
1. Install Jenkins onto an EC2 Server
2. Configure Jenkins and run the Build and Test stages
3. Install AWS EB CLI to your EC2 Instance
4. Add the Deploy Stage to the Jenkins file that will deploy the application to Elastic Beanstalk

## Systems Diagram

![Deployment3](Deployment3.jpg)

## Optimization
