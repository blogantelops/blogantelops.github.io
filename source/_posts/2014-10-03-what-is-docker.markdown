---
layout: post
title: "What is Docker"
date: 2014-10-03 12:10:43 +0200
comments: true
categories: [docker]
---

What is Docker?
===============
Docker is an open platform for developers and sysadmins to build, ship, and run distributed applications. Consisting of Docker Engine, a portable, lightweight runtime and packaging tool, and Docker Hub, a cloud service for sharing applications and automating workflows, Docker enables apps to be quickly assembled from components and eliminates the friction between development, QA, and production environments. As a result, IT can ship faster and run the same app, unchanged, on laptops, data center VMs, and any cloud.

<!-- MORE -->


Solomon Hykes, Docker’s Founder & CTO, gives an overview of Docker in this short video (7:16).

{% youtube ZzQfxoMFH0U %}


Why do developers like it?
==========================
With Docker, developers can build any app in any language using any toolchain. “Dockerized” apps are completely portable and can run anywhere - colleagues’ OS X and Windows laptops, QA servers running Ubuntu in the cloud, and production data center VMs running Red Hat.
Developers can get going quickly by starting with one of the 13,000+ apps available on Docker Hub. Docker manages and tracks changes and dependencies, making it easier for sysadmins to understand how the apps that developers build work. And with Docker Hub, developers can automate their build pipeline and share artifacts with collaborators through public or private repositories.
Docker helps developers build and ship higher-quality applications, faster.



Why do sysadmins like it?
=========================
Sysadmins use Docker to provide standardized environments for their development, QA, and production teams, reducing “works on my machine” finger-pointing. By “Dockerizing” the app platform and its dependencies, sysadmins abstract away differences in OS distributions and underlying infrastructure.
In addition, standardizing on the Docker Engine as the unit of deployment gives sysadmins flexibility in where workloads run. Whether on-premise bare metal or data center VMs or public clouds, workload deployment is less constrained by infrastructure technology and is instead driven by business priorities and policies. Furthermore, the Docker Engine’s lightweight runtime enables rapid scale-up and scale-down in response to changes in demand.
Docker helps sysadmins deploy and run any app on any infrastructure, quickly and reliably.
How is this different from Virtual Machines?
App A


Virtual Machines
----------------
Each virtualized application includes not only the application - which may be only 10s of MB - and the necessary binaries and libraries, but also an entire guest operating system - which may weigh 10s of GB.

Docker
------
The Docker Engine container comprises just the application and its dependencies. It runs as an isolated process in userspace on the host operating system, sharing the kernel with other containers. Thus, it enjoys the resource isolation and allocation benefits of VMs but is much more portable and efficient.


