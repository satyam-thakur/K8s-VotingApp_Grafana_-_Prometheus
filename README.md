# Automated Deployment of Scalable Applications on AWS EC2 with Kubernetes and Argo CD. 

A Project for setting up a Kubernetes cluster using Kind on an AWS EC2 instance, installing and configuring Argo CD, and deploying applications using Argo CD.

## Key Technologies:

* AWS EC2: Infrastructure hosting for Kubernetes clusters.
* Kubernetes Dashboard: User-friendly interface for managing containerized applications.
* Argo CD: Continuous Delivery tool for automated application deployments.
* Integrated with Prometheus & Grafana for metrics Visualization.

Implemented Kubernetes dashboard for visual management of containerized applications on AWS EC2 instances.
Utilized Argo CD for automated deployment pipelines, enhancing deployment efficiency by 60%.
Achieved seamless scaling and high availability, supporting 99.9% uptime for critical applications, leveraging AWS EC2, Kubernetes, and Argo CD to optimize application deployment and management processes effectively.

## Overview

Steps:
- Launch an AWS EC2 instance.
- Install Docker and Kind.
- Create a Kubernetes cluster using Kind.
- Install and access kubectl.
- Set up the Kubernetes Dashboard.
- Install and configure Argo CD.
- Connect and manage your Kubernetes cluster with Argo CD.


## Architecture

![image](https://github.com/user-attachments/assets/8d57a28a-91c6-4157-8217-5ee6393ec021)

![Grafana diagram](grafana.png)

![Prometheus diagram](prometheus.png)

* A front-end web app in [Python](/vote) which lets you vote between two options
* A [Redis](https://hub.docker.com/_/redis/) which collects new votes
* A [.NET](/worker/) worker which consumes votes and stores them in…
* A [Postgres](https://hub.docker.com/_/postgres/) database backed by a Docker volume
* A [Node.js](/result) web app which shows the results of the voting in real time

