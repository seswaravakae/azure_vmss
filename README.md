Prerequisites
Azure subscription: If you don't have an Azure subscription, create a free account before you begin.
Install Ansible: Do one of the following options:

Install and configure Ansible on a Linux virtual machine
Configure Azure Cloud Shell and - if you don't have access to a Linux virtual machine - create a virtual machine with Ansible.
Configure a scale set
The playbook code in this section defines the following resources:

Resource group into which all of your resources will be deployed.
Virtual network in the 10.0.0.0/16 address space
Subnet within the virtual network
Public IP address that allows you to access resources across the Internet
Network security group that controls the flow of network traffic in and out of your scale set
Load balancer that distributes traffic across a set of defined VMs using load balancer rules
Virtual machine scale set that uses all the created resources
