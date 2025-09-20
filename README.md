# memoraq-infra
This repo contains infrastructure for memraq project.
The provisioning is implemented using Ansible for both provisioning the nodes on Hetzner cloud and bootstrapping the k8s cluster.

# Architecture
The cluster is provisioned on Hetzner cloud using Ansible. The cluster consists of:
- 1 control pane
- 1 worker node
