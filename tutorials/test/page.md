---
layout: tutorial
title: links css
description: Part 1: Introduction and Navigation through the Best Practices Guide
tags: [tutorial:product/sapHana, tutorial:product/hana_studio, tutorial:technology/sql, tutorial:technology/amazon_aws, tutorial:product/hcp, tutorial:interest/gettingstarted, tutorial:product/hcp_web_workbench]
---
## Prerequisites  
[How to create an SAP HANA Developer Edition in the Cloud](http://go-qa.sap.com/developer/tutorials/setup-hana-for-cloud.html)

## Next Steps
Next steps is option, hence, may not be present.
[Hello World!](http://go-qa.sap.com/developer/tutorials/hana-web-development-workbench.html)

## Details

### You will learn  

1. How to use HANA Studio Perspectives
2. How to create a connection to the HANA back end
3. Getting started with the HANA Web based development workbench

### Time to Compete

Beginners will take 30 minutes to finish this tutorial.

## Outline

1. [Introduction and Navigator (this document)](http://go.sap.com/developer/tutorials/ci-best-practices-intro.html)  
2. Continuous Integration and Delivery  
2.1. [CI/CD Practices](http://go.sap.com/developer/tutorials/ci-best-practices-ci-cd.html)  
2.2. [Pipeline Suggestions](http://go.sap.com/developer/tutorials/ci-best-practices-pipelines.html)  
3. CI/CD Landscape - Component Setup  
3.1. [Source Code Versioning System](http://go.sap.com/developer/tutorials/ci-best-practices-scm.html)  
3.2. [Build Scheduler](http://go.sap.com/developer/tutorials/ci-best-practices-build.html)  
3.3. [Artifact Repository](http://go.sap.com/developer/tutorials/ci-best-practices-artifacts.html)  
3.4. [Landscape Configuration](http://go.sap.com/developer/tutorials/ci-best-practices-landscape.html)  
4. CI/CD Process Setup  
4.1. [Generic Project](http://go.sap.com/developer/tutorials/ci-best-practices-generic.html)  
4.2. [Java Web on SAP HANA Cloud Platform](http://go.sap.com/developer/tutorials/ci-best-practices-java-hcp.html)  

---


### links

> Это встроенная [ссылка с title элементом](http://example.com/link "Я ссылка"). Это — [без title](http://example.com/link).
> 1. Access the Gerrit front end with a browser on port 8080 and log on with your admin user.
> 2. Go to **Projects > Create New Project**. 
> 3. Enter the project name `HelloWorld` and select **Create initial empty commit**. This automatically creates the master branch.
> 4. Enter `Rights Inherit From:` `CI-Projects`[link without name](https://gerrit-review.googlesource.com/Documentation/cmd-create-project.html).
> test content

>- item1 [Generic Project123](http://go.sap.com/developer/tutorials/ci-best-practices-generic.html)
>     - one_one
>     - two [Generic Project321](http://go.sap.com/developer/tutorials/ci-best-practices-generic.html)
    
&nbsp;


>### Note
>If you have skipped the tutorial [Extend the YaaS Storefront's Functionality](http://go.sap.com/developer/tutorials/yaas-extend-storefront-functionality-webservice.html), you can clone the Tips Micro Service with this command. `git clone https://github.com/SAP/yaas-getting-started-yaasbites.git`
> 1. Access the Gerrit front end with a browser on port 8080 and log on with your admin user.
> 2. Go to **Projects > Create New Project**. 
> 3. Enter the project name `HelloWorld` and select **Create initial empty commit**. This automatically creates the master branch.
> 4. Enter `Rights Inherit From:` `CI-Projects`[link without name](https://gerrit-review.googlesource.com/Documentation/cmd-create-project.html).
> test content

>- item1 [Generic Project123](http://go.sap.com/developer/tutorials/ci-best-practices-generic.html)
>     - one_one
>     - two [Generic Project321](http://go.sap.com/developer/tutorials/ci-best-practices-generic.html)

&nbsp;


>### Warning
>If you have skipped the tutorial [Extend the YaaS Storefront's Functionality](http://go.sap.com/developer/tutorials/yaas-extend-storefront-functionality-webservice.html), you can clone the Tips Micro Service with this command. `git clone https://github.com/SAP/yaas-getting-started-yaasbites.git`
> 1. Access the Gerrit front end with a browser on port 8080 and log on with your admin user.
> 2. Go to **Projects > Create New Project**. 
> 3. Enter the project name `HelloWorld` and select **Create initial empty commit**. This automatically creates the master branch.
> 4. Enter `Rights Inherit From:` `CI-Projects`[link without name](https://gerrit-review.googlesource.com/Documentation/cmd-create-project.html).
> test content

>- item1 [Generic Project123](http://go.sap.com/developer/tutorials/ci-best-practices-generic.html)
>     - one_one
>     - two [Generic Project321](http://go.sap.com/developer/tutorials/ci-best-practices-generic.html)
    
&nbsp;

>### Caution
>If you have skipped the tutorial [Extend the YaaS Storefront's Functionality](http://go.sap.com/developer/tutorials/yaas-extend-storefront-functionality-webservice.html), you can clone the Tips Micro Service with this command. `git clone https://github.com/SAP/yaas-getting-started-yaasbites.git`
> 1. Access the Gerrit front end with a browser on port 8080 and log on with your admin user.
> 2. Go to **Projects > Create New Project**. 
> 3. Enter the project name `HelloWorld` and select **Create initial empty commit**. This automatically creates the master branch.
> 4. Enter `Rights Inherit From:` `CI-Projects`[link without name](https://gerrit-review.googlesource.com/Documentation/cmd-create-project.html).
> test content

>- item1 [Generic Project123](http://go.sap.com/developer/tutorials/ci-best-practices-generic.html)
>     - one_one
>     - two [Generic Project321](http://go.sap.com/developer/tutorials/ci-best-practices-generic.html)
    
&nbsp;

А вот [пример][1] [нескольких][2] [ссылок][id] с разметкой как у сносок. Прокатит и [короткая запись][] без указания id.

[1]: http://example.com/ "Optional Title Here"
[2]: http://example.com/some
[id]: http://example.com/links (Optional Title Here)
[короткая запись]: http://example.com/short


In this guide we will discuss some basic principles for software development that are derived from the process definitions for Continuous Integration (CI) and Continuous Delivery (CD). We will then break the principles down into the best practices that will support you in setting up an efficient development process for your cloud application development on SAP HANA Cloud Platform (SAP HCP).

We noticed that customers seek for more guidance on an end-to-end CI process. SAP offers several tools to address single aspects.
The goal of this guide is to provide recommendations that focus on the complete picture of a CI or CD process and how to set it
up using widely adapted complementary tools. The choice of tools should be considered as examples. Other tools fulfilling the same purpose will work as well.

We will examine the most important SAP technologies and describe how to use existing tools to set up a CI process that fits the individual needs of your development project, your requirements, and your environment.

Sometimes you want bullet points:

* Start a line with a star
* Profit!

You can create nested lists: 

* item1
    * one_one
    * two
