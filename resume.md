Senior full-stack architect with 18 years of professional experience.

# Summary

## Data

- Apache Spark
- Apache Hadoop Compute
- Apache Hadoop HDFS
- MongoDB
- Elasticsearch
- Redis
- SQL Server
- PostgreSQL
- MySQL

## Front-end

- AngularJS
- Angular
- React
- KnockoutJS
- MeteorJS
- ECMAScript 2015 - 2019
- SignalR

## Back-end

- ASP 3.0
- ASP.NET
- ASP.NET MVC
- ASP.Net WebAPI
- ASP.NET Core
- Express.js
- http-server
- Linux
- Babel
- SignaR

## Delivery

- Azure DevOps
- Azure YAML Pipelines
- Docker
- Docker Compose

## Cloud

- Azure
- AWS
- Google Cloud


# Experience 

## Cazton: Research

### MicroFrontend (MFE) 2020/10

Developed an MFE proof-of-concept using Single-SPA.  The individual applications were written in React and stitched together using Single-SPA.  The advantage of MFE designs is the constituent applications can be developed using any technology stack, but React was chosen for this proof-of-concept for speed of development.

#### Technologies

- Single-SPA
- React
- NodeJS http-server
- ECMAScript 2015 - 2019
- Git
- Linux
  

### Research: Hadoop Compute, Spark, HDFS 2020/09

Created an application as a research project to gain experience with Hadoop Compute, Spark, and HDFS.  The application utilized a gigabytes of NOAA weather data to compute various aggregates.  The problem was oringally solved with Python, then Hadoop Compute, and then finally Spark.

#### Technologies

- Python
- PySpark
- Apache Hadoop Compute
- Apache Hadoop Streams
- Apache Hadoop HDFS
- Apache Spark
- Git
- Linux
- Docker
- Docker Compose

## Cazton Client: Mortgage Industry 2018/08 - 2020/09

### Encompass Authority

Built a system of microservices that provided a mirror of a massive legacy system.  The data in the legacty system was poorly accessible, and the new system made the data queryable and allowing for realtime subscriptions.  The primary datastore managed billions of records in an RDBMS.

#### Technologies

- C#
- .NET Framework 4.5.2
- .NET Core
- ASP.NET Core
- gRPC
- Kerberos
- RabbitMQ
- MassTransit
- Multi-threading / Concurrency
- GraphQL
- PostgreSQL
- SQL Server
- Reactive Extensions (.NET)
- Git
- HAProxy
- Docker
- Docker Compose


### Encompass API Gateway

Built a gRPC service that replicated the Encompass SDK API, which required .NET Framework 4.5.2, and exposed the functionality via a gRPC interface, allowing any technology stack to integrate with Encompass via the SDK.

#### Technologies

- C#
- .NET Framework 4.5.2
- .NET Core
- Kerberos
- gRPC
- Git
  

### Encompass Loan Fees

Created a mechanism to refactor a user experience in a desktop application using the Chromium Embedded Framework.  Effectively, I created a web-powered UI within a legacy desktop application.

#### Technologies

- C#
- ECMAScript 2015 - 2019
- Chromium Embedded Framework (CefSharp)
- React
- Parcel bundler
- TypeScript
- Babel
- Git


### Point of Sale Adaptation

Took a codebase crated to replace the client's point-of-sale and adapted it to their needs.  This included integrating the web application with the back-end Encompass system.  The majority of my time on this project was spent mentoring other team members and unblocking them.

#### Technologies

- C#
- ECMAScript 2015 - 2019
- Knockout.JS
- ASP.NET MVC 4
- ASP.NET WebAPI
- SQL Server
- TypeScript
- Webpack
- Babel
- Git

### R&D: DevOps / CI-CD

Before engaging this client, they had no CI/CD automation.  In fact, many projects were not even stored in source control, and most applications were deployed from builds done on individual developer machines.  I organized the transition to Git for source control and installed automation for CI/CD through Azure Devops.

#### Technologies

- Git
- Azure DevOps
- Azure YAML Pipelines
- Docker

### Reusable Packages / Cross-cutting Concerns

Designed and implemented reusable NuGet package for the organization to use to handle cross-cutting concerns like logging, dependency injection, application hosting, etc.  Prior to these packages, every team implemented these concerns separately.

#### Technologies

- C#
- NuGet Packager
- Elasticsearch
- Logstash
- Git


## Cazton Client: Finance Industry 2014/05 - 2015/03

### R&D: Parallel and Streaming Multipart Uploads

The main product of the organization accepted uploaded files of arbitrary size, but found themselves running out of memory when file uploads exceeded a certain size.  Developed a replacement for an ASP.NET multipart upload handler that streamed files to the virus scanner and ultimately reduced memory pressure and removed limits on file upload size.

- C#
- WCF
- ASP.NET WebAPI
- Git

### R&D: PDF Generation Library

Developed a replacement for the existing, paid, closed-source PDF generation in order to allow the organization to quickly generate PDF invoices from Razor templates.

- EvoPDF
- C#
- Razor Generator
- Git

### R&D: R2 DSL / Code Generation Library

Created a code generation library called R2, which implemented a DSL to allow developers to define request/response contracts using a markup language.  The code generation library would then generate all of the scaffolding for the handlers, tests, etc.

#### Tehchnologies

- C#
- XML/XSD
- T4 Templating Engine
- MSBuild Extensibility
- Git

### Full-stack Primary Product Development

Assisted the product development team on an Angular.JS project by augmenting their staff and implementing features.

#### Technologies

- C#
- ECMAScript 2015 - 2016
- Babel
- ElasticSearch
- Angular.JS
- ASP.NET MVC
- ASP.NET WebAPI
- SQL Server

## SiteZeus 2017/09 - 2018/06

### CI/CD Pipeline using VSTS

Introduced the organization to automated CI/CD using Azure Devops.

#### Technologies

- Git
- TFS
- Azure DevOps
- Azure DevOps Builds and Releases
- XUnit Testing


### Migration from TFS to Git

The source code was originally stored in TFS; I managed the migration to Git and automated building, testing, and deploying.

- Git
- TFS
- Azure DevOps


### Redis Caching

The main product for the organization cached expensive computations, but did so with local server memory.  I managed the migration from memory caches to a shared, distributed cache using Redis.

- C#
- Redis


### SSO/SAML Infrastructure

I implemented the ability to log into the application using SSO/SAML.  This allowed corporate clients to connect with their corporate credentials instead of having to maintain separate credentials for our application.

#### Technologies

- SAML
- Encrypted XML
- Encryption and Hashing/Signing
- ASP.NET
- ASP.NET WebAPI


### Architecture and Testing Improvements

I completely reorganized the architecture of the main project to enable dependency injection of individually testable components.  Then, I integrated a testing framework and mentored the team on using it to implements their own tests using mocks and other constructs.

#### Technologies

- C#
- Git
- XUnit
- Dependency Injection


### Puppeteer Microservice

We had a need to use automation to log in to our application, perform some actions, take a screenshot of the result, and return it to a user.  This is because the application did have an API to do this in a more straightforward way.  I chose Puppeteer to perform the automation.

- C#
- Puppeteer.JS
- Microservices
- Docker
- Azure Container Registry
- Azure Container Instance
- Git


### Realtime Data with SignalR

The existing application maintained an up-to-date UI by polling for information periodically.  I created a framework using SignalR, Rx.NET, and Rx.JS to allow developers to push data instead of having to periodically poll.

#### Technologies

- C#
- Git
- Rx.NET
- RX.JS
- ECMAScript 2015 - 2017
- Babel
- SignalR


## Person and Partners - 2012/10 - Present

### Custom Data Integration Platform

I developed and maintain an application in Meteor.JS that connects mutliple vendors of data, and multiple lead sources like HTML forms, Facebook Leadgen, Google Web Hooks, and others.  The leads integration with the individual clients' CRM via this platform.

#### Technologies

- ECMAScript 5 - 2019
- Babel
- Webhook
- MeteorJS
- MongoDB
- Facebook API
- Search Ads 360 API
- Google Ads API
- ADF / XML


## Price Waterhouse Coopers (PwC) - 2017/01 - 2017/07

### Established New Project Architecture and Patterns

The company was going through an upheaval and reorganization.  We began a project, but there was no acrhictectural guidance so every developer was working differently.  I implemented and shared patterns for building our application using Angular.

## Technologies

- C#
- Git
- Azure DevOps
- ASP.NET Core
- Angular


### Established Code Review Process

Before my joining the team, all code was committed without any kind of code review.  The team did not know how to use Git pull requests to achieve this purpose, so I instituted branch policies to require all code to be reviewed.

- C#
- Git
- Azure DevOps
- Pull Requests
- Azure DevOps Git Branch Security


### Mentoring Team Members

Due to organizational restructuring, the team had no development leadership.  I took on this role.

- C#
- Git
- Azure DevOps
- Pull Requests
- Azure DevOps Git Branch Security


## Tribridge - 2016/03 - 2016/10

### Synchronization Framework

One of the major promised features of the application was a push-based constant upate of the UI.  I implemnted a framework for the team to use to make this feature available.

#### Technologies

- C#
- ASP.NET 
- ASP.NET WebAPI
- Entity Framework
- SQL Server
- Redis
- SignalR


### Android Mobile Printing Infrastructure




## Jabil Circuit - 2015/08 - 2016/02



## Wolters Kluwer - 2013/10 - 2014/05

### Proxy KnockoutJS Extender

### Filtered KnockoutJS Extender

### Transactional KnockoutJS Extender

### Multilingual KnockoutJS Mapping Extensions

### Model Metadata Mechanism



## Agile Thought - 2012/08 - 2013/09

### Reflection Helper

### Document Direct Client

### Asynchronous Integrations

### PhoneGap Alternative



## Alter Ego - 2006/08 - 2012/12

### Stock Watch

### Price Reader

### EQ Login



## interCLICK - 2009/06 - 2010/12

### Astoria

### jQuery MVC

### Blocks



## ByDesign Technology - 2009/05 - 2009/06



## Kowabunga - 2008/10 - 2009/05



## Cronic Software - 2005/01 - 2005/112



## DSC Web Services - 2003/03 - 2005/01

