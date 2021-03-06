---
layout: global
displayTitle: Apache Spark on Kubernetes
title: Apache Spark on Kubernetes
description: User Documentation for Apache Spark on Kubernetes
---

### Overview

This site is for user documentation for running Apache Spark with a native Kubernetes scheduling backend. 
This repository [apache-spark-on-k8s/spark](https://github.com/apache-spark-on-k8s/spark), 
contains a fork of Apache Spark that enables running Spark jobs natively on a Kubernetes cluster.

### What is this?

This is a collaboratively maintained project working on 
[SPARK-18278](https://issues.apache.org/jira/browse/SPARK-18278). 
The goal is to bring native support for Spark to use Kubernetes as a cluster manager, 
in a fully supported way on par with the Spark Standalone, Mesos, and Apache YARN cluster managers.

### Relation with apache/spark

This project was put up for voting in [an SPIP](http://apache-spark-developers-list.1001551.n3.nabble.com/SPIP-Spark-on-Kubernetes-td22147.html)
in August 2017 and passed. It is in the process of being
upstreamed into the apache/spark repository.


### Contents

* [Running Spark on Kubernetes](./running-on-kubernetes.html)
* [Running Spark in Cloud Environments](./running-on-kubernetes-cloud.html)
* [Contribute](./contribute.html)