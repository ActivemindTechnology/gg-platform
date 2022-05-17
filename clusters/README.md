# Clusters

The base directory holds configuration which is common to all environments. It is not expected to change often. If you want to do changes to multiple environments at the same time, it is best to use the “variants” folder.

The variants folder holds common characteristics between environments.

![Kubernetes Clusters](../docs/images/readme/k8scluster.png?raw=true)

## dev-test Cluster

The dev-test cluster will not contain any real user data. Masked data may be used for testing. 

## stage-prod Cluster 
The stage-prod cluster will contain real user data. Staging will be a mirror of production. 