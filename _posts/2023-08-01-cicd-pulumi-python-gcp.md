---
title: "Modern Infrastructure as Code: Using Python with Pulumi for CI/CD on Google Cloud Platform"
date: 2023-08-01T11:34:30+12:00
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Pulumi
  - GCP
  - CI/CD
  - Python
---

I am embarking on the journey of building modern cloud applications with infrastructure as code (IaC) using Python and Pulumi based on Terraform YAML configs. 
Pulumi, an open-source infrastructure as code tool, lets you create, deploy, and manage infrastructure on any cloud using your favorite programming languages. Python, with its simple syntax and rich ecosystem, is one of the supported languages for Pulumi.

The ability to express infrastructure as  code unleashes one from the YAML constraints. The Pulumi platform with it's rich support of many of the current programming languages is refreshing but as with any new platform requires exploration and sometimes bridging the GAPS. The significance of infrastructure as code (IaC) and continuous integration/continuous delivery (CI/CD) practices cannot be understated. IaC enables developers to manage and provision their cloud resources using code, bringing the same rigor to infrastructure management as we have with software development. CI/CD, on the other hand, provides an automated approach for building, testing, and deploying applications to production in a reliable, repeatable manner. Combining these practices sets the foundation for DevOps culture, promoting rapid, consistent, and reliable delivery of applications. 


In this context, we're going to explore and fill in some gaps on how to leverage Pulumi with Python for IaC targeting GCP, along with Google Cloud Platform (GCP) for CI/CD. 

We'll not take a closer look at how to define and manage GCP resources using Pulumi's Python SDK but focus on how to integrate a basic example of this setup into a CI/CD pipeline, and how this can streamline the application deployment process. You'll learn to automate the creation and management of your GCP resources like Google Cloud Storage, while ensuring consistency, repeatability, and efficiency in your deployments.

By the end of this guide, you'll have an  operational configuration for infrastructure as code using Pulumi with Python, and integrating this setup with CI/CD on Google Cloud Platform. Let's get started.

<!--more-->

This work has been based on the good documentation for CI/CD and Google Cloud Build using NodeJs as Pulumi IaC language
# Existing documentation for NodeJS

The .......

```bash
gcloud builds submit .
```

WIP 