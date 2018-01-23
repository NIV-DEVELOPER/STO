# STO

This project shows a solution for storage management between Kubernetes and Storage products.

Welcome everybody to contributing this project.


# Our vision:

1. Automatic storage cluster deployment.
   a. single kind, single storage cluster
   b. single kinds, multiple storage clusters 
   c. multiple kinds, multiple storage clusters

1. Storage cluster scale up
   a. add one new storage cluster
   b. add new node to existed storage cluster
   c. do not support scale down the storage cluster

1. Data backup and recovery

1. Tenant management
   a. kubernetes namespace
   b. kubernetes RBAC

1. [CSI](http://blog.kubernetes.io/2018/01/introducing-container-storage-interface.html) and FlexVolume
   a. deploy CSI plugin to kubernetes node

1. Tenant resource quota
   a. limit the tenant(namespace) storage quota
   b. limit the volume size

1. Storage metrics
   a. accurate metrics, maybe [prometheus](https://prometheus.io/) 

1. Parameter template
   according to user's demands, serve some optional or recommanded parameter templates of storage cluster.

1. Storage images
   make many kinds of storage docker images.
