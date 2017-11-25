# Awesome Cloud Native Tutorials [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of tutorials and labs for learning cloud native concepts.

<br>

What is Cloud Native? From the [Cloud Native Computing Foundation](https://www.cncf.io/)'s FAQ:

> Cloud native computing uses an open source software stack to be:
> 1. Containerized. Each part (applications, processes, etc) is packaged in its own container. This facilitates reproducibility, transparency, and resource isolation.
> 1. Dynamically orchestrated. Containers are actively scheduled and managed to optimize resource utilization.
> 1. Microservices oriented. Applications are segmented into microservices. This significantly increases the overall agility and maintainability of applications.


## Contents

- [Containers](#containers)
  - [Docker](#docker)
  - [Open Containers](#open-containers)
- [Container Orchestration](#container-orchestration)
  - [Kubernetes](#kubernetes)
  - [Mesos](#mesos)
  - [OpenShift](#openshift)
- [Inter-Service Communication](#inter-service-communication)
- [Observability](#observability)
  - [Tracing](#tracing)
  <!-- Add monitoring/metrics and logging here -->


## Containers

### Docker

- [Please Contain Yourself](https://github.com/dylanlrrb/Please-Contain-Yourself) - A tutorial for those brand-new to Docker.
- [Dockerizing a Node.js application](https://github.com/docker/labs/tree/master/developer-tools/nodejs/porting) - A complete introduction to running an application inside a container.

### Open Containers

- [cri-o Tutorial](https://github.com/kelseyhightower/cri-o-tutorial) - Use cri-o to run containers in Kubernetes.


## Container Orchestration

- [Container Orchestration Comparisons](https://github.com/thesandlord/container-orchestration-comparisons) - Incomplete, but contains a good set up comparison.

### Kubernetes

- [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way) - The definitive guide to building a Kubenetes cluster from scratch.
- [service-catalog Tutorial](https://github.com/manifoldco/service-catalog-tutorial) - An overview of using service-catalog to provision services in your cluster.
- [Using kubeadm to Create a Cluster](https://kubernetes.io/docs/setup/independent/create-cluster-kubeadm/) - Install Kubernetes on a set of machines.
- [Kubernetes in AWS with kops](https://github.com/kubernetes/kops/blob/master/docs/aws.md) - Set up a kubernetes cluster in AWS using kops.

### Mesos

- [How to create a Mesos framework in Go](https://github.com/sayden/minimal-mesos-go-framework) - A tutorial showing Mesos' extensibility model.

### OpenShift

- [Local Cluster Management](https://github.com/openshift/origin/blob/master/docs/cluster_up_down.md) - Run a local OpenShift cluster on your laptop.


## Inter-Service Communication

- [Go gRPC Tutorial](https://github.com/phuongdo/go-grpc-tutorial) - An introduction to working with gRPC for Go Developers.
- [Implementing Remote Procedure Calls With gRPC and Protocol Buffers](https://scotch.io/tutorials/implementing-remote-procedure-calls-with-grpc-and-protocol-buffers) - Implement a Node.js gRPC server and call it from Node.js and Python.


## Observability

### Tracing

- [Tracing HTTP request latency in Go with OpenTracing](https://medium.com/opentracing/tracing-http-request-latency-in-go-with-opentracing-7cc1282a100a) - Introduction to tracing with Zipkin, with an addendum for using Jaeger.
- [OpenTracing Tutorials](https://github.com/yurishkuro/opentracing-tutorial) - A collection of tracing tutorials in Go, Java, Python, and Node.js by the author of the above Medium post.


## Contribute

Contributions welcome! Read the [contribution guidelines](./github/CONTRIBUTING.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Manifold has waived all copyright and
related or neighboring rights to this work.
