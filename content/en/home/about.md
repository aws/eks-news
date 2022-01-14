---
title: "About EKS"
image: "EKS.webp"
weight: 99
---

[Amazon Elastic Kubernetes Service (Amazon EKS)](https://aws.amazon.com/eks/) is a managed service that you can use to run [Kubernetes](https://kubernetes.io/) on [AWS](https://aws.amazon.com/) without needing to install, operate, and maintain your own Kubernetes control plane or nodes. Kubernetes is an open-source system for automating the deployment, scaling, and management of containerized applications. Amazon EKS:

* Runs and scales the Kubernetes control plane across multiple AWS Availability Zones to ensure high availability.
* Automatically scales control plane instances based on load, detects and replaces unhealthy control plane instances, and it provides automated version updates and patching for them.
* Is integrated with many AWS services to provide scalability and security for your applications, including the following capabilities:
  * [Amazon ECR](https://aws.amazon.com/ecr/) for container images
  * [Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) for load distribution
  * [IAM](https://aws.amazon.com/iam/) for authentication
  * [Amazon VPC](https://aws.amazon.com/vpc/) for isolation
* Runs up-to-date versions of the open-source Kubernetes software, so you can use all of the existing plugins and tooling from the Kubernetes community. Applications that are running on Amazon EKS are fully compatible with applications running on any standard Kubernetes environment, no matter whether they're running in on-premises data centers or public clouds. This means that you can easily migrate any standard Kubernetes application to Amazon EKS without any code modification.

Source: [What is Amazon EKS?](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html)

You can find the [containers roadmap on GitHub](https://github.com/aws/containers-roadmap). Follow any specific issues there you want to keep informed about to be notified when they ship.
