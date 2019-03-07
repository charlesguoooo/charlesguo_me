---
layout: post
title: k8s中的controllers
categories: [kubernetes, controllers]
description: kubernetes controller manager describe
keywords: kubernetes, controllers
---

### kubernetes controllers

从逻辑上来说的话,kubernetes的每一个controller应该算是一个独立的process,但是为了降低复杂性,这些controllers被编译到了一个二进制文件,作为一个process来运行.

从kubernetes在Github上的代码库来看,kubernetes controllers大概有下面这些

* bootstrap
* certificates
* cloud
* clusterroleaggregation
* cronjob
* daemonset
* deployment
* disruption
* endpoint
* grabage
* history
* job
* namespace
* nodeipam
* nodelifecycle
* podautoscaler
* podgc
* replication
* resourcequota
* service
* serviceaccount
* statefulset
* route
* volume
