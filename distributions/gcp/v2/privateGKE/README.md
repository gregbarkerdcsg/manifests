# Private GKE Resoruces

* This directory contains CNRM patches and resource definitions in order
  to deploy Kubeflow on private GKE.

# VPC Network

## distributions/gcp/ kpt setters to use if VPC is in the same project as the cluster
* network-ref-name 
* router-ref-name
* subnetwork-ref-name

## distributions/gcp/ kpt setters to use if the VPC is in a different project
* network-ref-external
* router-ref-external
* subnetwork-ref-external

## VPC Notes
Network, router, and subnetwork should all be in the same project, so don't mix and match.