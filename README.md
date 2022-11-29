# Build-a-severless-Web-Application-using-AWS
Building a Serverless Web Application using AWS


Skip to main content
Click here to return to Amazon Web Services homepage
Contact Us
Support 
English 
My Account 
Sign In 
re:Invent Products Solutions Pricing Documentation Learn Partner Network AWS Marketplace Customer Enablement Events Explore More
Getting Started Resource Center
Getting Started / Hands-on / ...

Getting Started with AWS
Build a Serverless Web Application
with AWS Lambda, Amazon API Gateway, AWS Amplify, Amazon DynamoDB, and Amazon Cognito
Build a Serverless Web Application

INTRODUCTION

HOST A STATIC WEBSITE

MANAGE USERS

BUILD A SERVERLESS BACKEND

DEPLOY A RESTFUL API

TERMINATE RESOURCES
Introduction: Build a Serverless Web Application
Follow step-by-step instructions to create a simple serverless web application that enables users to request unicorn rides from the Wild Rydes fleet
Overview
In this tutorial, you'll create a simple serverless web application that enables users to request unicorn rides from the Wild Rydes fleet. The application will present users with an HTML based user interface for indicating the location where they would like to be picked up and will interface on the backend with a RESTful web service to submit the request and dispatch a nearby unicorn. The application will also provide facilities for users to register with the service and log in before requesting rides.
Prerequisites
To complete this tutorial, you will need an AWS account, an account with ArcGIS to add mapping to your app, a text editor, and a web browser. If you don't already have an AWS account, you can follow the Setting Up Your AWS Environment getting started guide for a quick overview.

Application architecture
The application architecture uses AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console. Amplify Console provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.


Static Web Hosting

AWS Amplify hosts static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user's browser.

User Management

Amazon Cognito provides user management and authentication functions to secure the backend API.


Serverless Backend

Amazon DynamoDB provides a persistence layer where data can be stored by the API's Lambda function.


RESTful API

JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway.

 AWS experience
Beginner
 Time to complete
2 hours
 Cost to complete
Each service used in this architecture is eligible for the AWS Free Tier. If you are outside the usage limits of the Free Tier, completing this tutorial will cost you less than $0.25*.
 Requires
Technologies used:

An AWS account**
An ArcGIS account to add mapping to your app
A text editor
Recommended browser: The latest version of Chrome
AWS Lambda
Amazon API Gateway
AWS Amplify
Amazon DynamoDB
Amazon Cognito

*This estimate assumes you follow the recommended configurations throughout the tutorial and terminate all resources within 24 hours.
**Accounts that have been created within the last 24 hours might not yet have access to the resources required for this tutorial.
 Last updated
October 12, 2022

Modules
This tutorial is divided into five modules. Each module describes a scenario of what we're going to build and step-by-step directions to help you implement the architecture and verify your work. 

Host a Static Website (15 minutes): Configure AWS Amplify to host the static resources for your web application with continuous deployment built in
Manage Users (30 minutes): Create an Amazon Cognito user pool to manage your users' accounts
Build a Serverless Backend (30 minutes): Build a backend process for handling requests for your web application
Deploy a RESTful API (15 minutes): Use Amazon API Gateway to expose the Lambda function you built in the previous module as a RESTful API
Terminate Resources (10 minutes): Terminate all the resources you created throughout this tutorial
Host a Static Website
Learn About AWS
What Is AWS?
What Is Cloud Computing?
AWS Diversity, Equity & Inclusion
What Is DevOps?
What Is a Container?
What Is a Data Lake?
AWS Cloud Security
What's New
Blogs
Press Releases
Resources for AWS
Getting Started
Training and Certification
AWS Solutions Portfolio
Architecture Center
Product and Technical FAQs
Analyst Reports
AWS Partners
Developers on AWS
Developer Center
SDKs & Tools
.NET on AWS
Python on AWS
Java on AWS
PHP on AWS
JavaScript on AWS
Help
Contact Us
File a Support Ticket
Knowledge Center
AWS re:Post
AWS Support Overview
Legal
AWS Careers
Amazon is an Equal Opportunity Employer: Minority / Women / Disability / Veteran / Gender Identity / Sexual Orientation / Age.
Language عربي Bahasa Indonesia Deutsch English Español Français Italiano Português Tiếng Việt Türkçe Ρусский ไทย 日本語 한국어 中文 (简体) 中文 (繁體)
Privacy | Site Terms | Cookie Preferences | © 2022, Amazon Web Services, Inc. or its affiliates. All rights reserved.
