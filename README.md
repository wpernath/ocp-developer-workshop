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
The next iteration of this Architecture Workshop happens on Feb 1st 2022 to Feb 2ndl 2022. Times in Central European Time.

### Day #1
Start | End | Topics
------|-----|------
9:00 | 9:30| Intro & Welcome
9:30 | 10:30| Kubernetes and OpenShift
**10:30**|**10:45**| **break**
10:45|12:15|Introduction to Quarkus - What is Quarkus - First steps with Quarkus Creating REST CRUD services
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

## Resources
The slides and presentations can be found in this repository.

- [Intro](material/1_Introduction%20to%20Red%20Hat%20OpenShift%20for%20Developers.pdf)
- [Application Packaging](material/2_Application%20Packaging.pdf)
- [ServiceMesh & Serverless](material/3_ServiceMesh%20&%20Serverless.pdf)
- [CI/CD & GitOps](material/4_CI_CD.pdf)

## Demo Repositories & Requirements
All sources and demos are publicly available on GitHub. 
- [Basic Book Examples](https://github.com/wpernath/book-example.git)
- [Basic Book Example Config](https://github.com/wpernath/person-service-config.git)
- [Advanced Example](https://github.com/wpernath/light-control.git)
- [Advanced Example Config](https://github.com/wpernath/light-control-config.git)


## Addional Resources
If you want to deepen your knowledge on several topics, have a look at the following blog series on **Automated Application Packaging and Distribution with OpenShift** which you could read here: 

- [Chapter zero](https://www.opensourcerers.org/2021/12/20/how-to-quickly-create-a-crud-service-with-quarkus/) talks about creating the CRUD service with Quarkus.

- [Chapter one](https://www.opensourcerers.org/2021/04/26/automated-application-packaging-and-distribution-with-openshift-part-12/) talks about container images and explains all the basic files and gives you a guide through OpenShift Templates and Kustomize as a base technology for application packaging
- [Chapter two](https://www.opensourcerers.org/2021/05/24/automated-application-packaging-and-distribution-with-openshift-part-23/) provides an overview of the various packaging formats, namely Helm Charts and Kubernetes Operators, and explains how they differ from each other and how to create them
- [Chapter three](https://www.opensourcerers.org/2021/07/26/automated-application-packaging-and-distribution-with-openshift-tekton-pipelines-part-34-2/) gives you a detailed view of Tekton / OpenShift Pipelines and helps you to quickly start your CI/CD process
- [And finally chapter four](https://www.opensourcerers.org/2021/09/06/automated-application-packaging-and-distribution-with-openshift-gitops-and-argocd-part-44) provides a detailed overview of GitOps and how to use it with OpenShift. 

