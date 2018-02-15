# CME Workbench
A DevOps toolkit for kubernetes on AWS. The workbench makes processes in a microservice world visible for developers in a non-console way.
CME is short for Consort Microservice Experience.

The toolkit is build for a medium to large size microservice setup with more than one team working in local, dev and production environments.

The toolkit addresses some of the **real world challenges** like 
- cloud security, 
- automated documentation, 
- advanced testing, 
- tool integration and 
- cost control.

<aside class="notice">
CME Workbench is advanced tooling and requires some time to adapt to your infrastructure! For example the UI is secured by JWTs issued by a state-of-the-art IAM service as well as any services involved.
</aside>

## What is it good for?

CME Workbench is a Angular UI with several backend microservices. The UI is used by DevOps staff to tackle daily challenges ranging from "create a new microservice" to "calculate the monthly costs for project XY".

The Workbench provides 30% of all use cases for an enterprise level project. Your team can enhance the toolkit with own microservices and Angular Components.

**There is no commercial version of the toolkit and there are no licenses or fees.**

## Technical requirements

You should have some kind of Kubernetes cluster running as well as a AWS account.

![basic setup](https://github.com/consort-it/cme-workbench/blob/master/img/setup.PNG)

Typically you have a lot of tooling already in place. We provide a set of tooling adapters for the most common services like GitLab or Jenkins. Because **all components are open source** you can adapt the workbench to any DevOps configuration.

There is no setup necessary apart from installing the adapters in a separate Kubernetes namespace and a AWS Cognito Userpool. You can even run the CME Workbench UI locally.
