# Architecture Workshop - OpenShift Developers
## What is it?
The Architecture workshop - OpenShift developer is a two-day learning experience for developers who want to understand and make use of the benefits of OpenShift in their daily work. They learn everything they need to understand the concepts, the architectural principles and components of OpenShift and related products for successfully discussing and developing OpenShift at a customer site from a developer’s perspective.

## Key Takeaways
- Benefits of OpenShift prior plain Kubernetes
- How to effectively demo OpenShift from a Developer’s perspective
- Understanding OpenShift ServiceMesh (istio.io)
- Understanding and using Quarkus to build a micro service
- Developing with OpenShift 
- Using Source to Image
- Understanding Serverless (Knative)
- Service Binding
- Using OpenShift Templates and Kustomize to redeploy your Application
- Creating and Using Helm Charts and Kubernetes Operators
- Use OpenShift Pipelines (Tekton Pipelines) to do CI/CD
- Use of ArgoCD and OpenShift GitOps

## Target Audience
- Sales Engineers
- Delivery
- Solution Architects
- Developers

## Prerequisites
- Basic knowledge of Red Hat 
- Basic understanding of Containers and Container Images
- Basic understanding of OpenShift and / or Kubernetes
- Java or any other programming language

## AGENDA
The next iteration of this Architecture Workshop happens on June 13th 2023 to June 14th 2023. Times in Central European Time.

If you want to participate, please go [here](https://www.redhat-partner.com/enablement/trainings/register/278/) and register for free.

### Day #1
Start | End | Topics
------|-----|------
9:00 | 9:30| Intro & Welcome
9:30 | 10:30| Kubernetes and OpenShift
10:30| 11:00| Podman Desktop
**11:00**|**11:15**| **break**
11:15|12:15|Introduction to Quarkus - What is Quarkus - First steps with Quarkus Creating REST CRUD services
**12:15**|**13:15**|**Lunch Break**
13:15|15:30|Application Packaging - Templates - Kustomize - DIY - Helm Charts - Kubernetes Operators
15:30|16:00|Open Questions / Answers


### Day #2
Start | End | Topics
------|-----|------
9:00 | 9:15| Welcome
9:15 | 10:45| Advanced Topics - Serverless - ServiceMesh
**10:45**|**11:00**| **break**
11:00|12:30|CI/CD - OpenShift Pipelines - Tekton - Tekton Security - Working with the examples
**12:30**|**13:30**|**Lunch Break**
13:30|15:30|GitOps - Basics / Concepts - Using ArgoCD - Working with the examples - Building a complete demo
15:30|16:00|Open Questions / Answers

## Recordings
Please have a look at the latest recordings of the workshop here:

Date | Time | Description
-----|-------|------------
Dec 14 2022 | [9:00am - 12:00am](https://drive.google.com/file/d/1H-AfeqH5ADwowEBYagI46c4U51Cn5BHd/view?usp=share_link) | Morning session - General, Quarkus Demo 
Dec 14 2022 | [13:00pm - 15:15am](https://drive.google.com/file/d/1gF9BcHCIOWxZvWDWKUBuetDvB-FUACt2/view?usp=share_link) | Afternoon session - Templates, Helm, Kustomize, Operators
Dec 15 2022 | [9:00am - 12:00am](https://drive.google.com/file/d/1O6Pz9uiduJcsRUBKEqe4VGRP3Ds1wsKs/view?usp=share_link) | Morning session - Knative, ServiceMesh, Tekton
Dec 15 2022 | [13:00pm - 15:00pm](https://drive.google.com/file/d/1jH4piMoHufvRltZKqem5Mli3i5gGsDe6/view?usp=share_link) | Afternoon session - GitOps, ArgoCD, Working with the example

## Resources
The slides and presentations can be found in this repository.

- [Intro](material/1_Introduction%20to%20Red%20Hat%20OpenShift%20for%20Developers.pdf)
- [Application Packaging](material/2_Application%20Packaging.pdf)
- [ServiceMesh & Serverless](material/3_ServiceMesh%20&%20Serverless.pdf)
- [CI/CD & GitOps](material/4_CI_CD.pdf)

## Accompanying eBook
The accompanying free eBook of this workshop is [Getting GitOps](https://developers.redhat.com/e-books/getting-gitops-practical-platform-openshift-argo-cd-and-tekton), which has been published by [Red Hat Developers](https://developers.redhat.com/). 

## Demo Repositories & Requirements
All sources and demos are publicly available on GitHub. 
- [Basic Book Examples](https://github.com/wpernath/book-example.git)
- [Basic Book Example Config](https://github.com/wpernath/person-service-config.git)
- [KNative / Serverless Workshop](https://github.com/wpernath/knative-workshop)
- [Quarkus Quickstart](https://github.com/wpernath/quarkus-worldtour)
- [GrumpyCat Example Game](https://github.com/wpernath/quarkus-grumpycat.git)
- [GrumpyCat Example Config](https://github.com/wpernath/grumpycat-config.git)
- [Advanced Example](https://github.com/wpernath/light-control.git)
- [Advanced Example Config](https://github.com/wpernath/light-control-config.git)


## Addional Resources
If you want to deepen your knowledge on several topics, have a look at the following blog series on **Automated Application Packaging and Distribution with OpenShift** which you could read here: 

(BTW, the blog series has been rewritten and published by [RedHat Developers](https://developers.redhat.com/e-books/getting-gitops-practical-platform-openshift-argo-cd-and-tekton)). 

- [Chapter zero](https://www.opensourcerers.org/2021/12/20/how-to-quickly-create-a-crud-service-with-quarkus/) talks about creating the CRUD service with Quarkus.

- [Chapter one](https://www.opensourcerers.org/2021/04/26/automated-application-packaging-and-distribution-with-openshift-part-12/) talks about container images and explains all the basic files and gives you a guide through OpenShift Templates and Kustomize as a base technology for application packaging
- [Chapter two](https://www.opensourcerers.org/2021/05/24/automated-application-packaging-and-distribution-with-openshift-part-23/) provides an overview of the various packaging formats, namely Helm Charts and Kubernetes Operators, and explains how they differ from each other and how to create them
- [Chapter three](https://www.opensourcerers.org/2021/07/26/automated-application-packaging-and-distribution-with-openshift-tekton-pipelines-part-34-2/) gives you a detailed view of Tekton / OpenShift Pipelines and helps you to quickly start your CI/CD process
- [And finally chapter four](https://www.opensourcerers.org/2021/09/06/automated-application-packaging-and-distribution-with-openshift-gitops-and-argocd-part-44) provides a detailed overview of GitOps and how to use it with OpenShift. 

