---
title: "Data Pipe Dev Kit"
summary: "Lorem ipsum dolor sit amet"
date: "Oct 18 2024"
draft: false
tags:
- GNU Make
- Kubernetes
- Orbstack
- CockroachDB
- PostGRESQL
- Memphis
- MageAI
repoUrl: https://github.com/aRustyDev/minikube-dev-kit
---

# Data Pipe Dev Kit

This is an offshoot of my work with the Datamesh Platform. I created this to enable other analysts to begin quickly setting up local 
versions of the data mesh on a small scale, so they could test out their own transform logic w/o needing to push to the production 
infrastructure. It started as a collection of Make files that would deploy a 3 layer datapipe on a local minikube instance, butsince my 
organization is macOS by default, I ended up converting from minikube to [Orbstack](https://orbstack.dev/). Which is a macOS native 
platform to replace docker desktop and has native support for kubernetes, at a fraction of the resource overhead of docker.
