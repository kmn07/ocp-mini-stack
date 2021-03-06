# CCIO OCP MiniStack Education & Development Lab
### Get Started:
  + [01 Host Hypervisor - Bare Metal]
  + [02 CloudCtl RDP Bastion - LXD Container]
  + [03 VFW Firewall & Gateway - LXD Container]
  + [04 DNS & DHCP Service			- OCI Podman Container]
  + [05 Application Router Proxy - OCI Podman Container]
  + [06 Simple Artifact Server - OCI Podman Container]
  + [07 TFTP Boot Artifact Server - OCI Podman Container]
  + [08 Deploy OpenShift Red Hat CoreOS Nodes]
     
---------------------------------------------------------------------------------
     
![CCIO_OCP MiniStack Lab_Diagram](zweb/drawio/master-ocp-mini-stack.svg)

## What is it?
Intended for both the new hobby sysadmin and experienced DevOps professional.    
This set of guides & build tools is aimed at the Single Host Laptop/Desktop/Server Development and Education Paradigm and can be expanded upon once the core fundamentals are understood.    
    
By following these guides you will be able to:    
  1. Demostrate the significant potential of reasonably equipped hardware    
  2. Improve your understandng and fluency in fitting common commercial software components together    
  3. Overcome barriers in consuming automation tools to improve your workflow beyond the burden of menial tasks    
    

## Purpose:

This tooling provides a common platform to quickly and seamlessly build virtual environments.    
    
The original inspiration for this project came from endless hours of testing different 
virtual network building tools and strategies in search of a paradigm that meets a 
number of criteria included in the following.
    
#### The tooling also needs to be consistent across hardware platforms including:    
  + Client Laptops
  + Client Desktops
  + Low cost Home Labs
  + DevOps Lab Servers
  + 100% Virtual Tenants
  + Multi-Host Rack Systems
    
#### Easy end-user management and setup:    
  + Logical to comprehend
  + Easy to setup
  + Easy to manage
  + Capable of multi-host overlays
  + Easy to use over Wifi connections
  + Capable of nesting multiple layers of networks
    
#### Easy integration of technologies including:
  + Docker/Podman Application Container OCI Runtimes
  + LXD / LXC OS Container Runtimes
  + Libvirt / QEMU / KVM Virtual Machine Environments
  + Kubernetes
  + Bare Metal Hosts
  + Physical & Virtual Switching Gear

<!-- Markdown link & img dfn's -->
[01 Host Hypervisor				- Bare Metal]:/01_HostSetup.md
[02 CloudCtl RDP Bastion		- LXD Container]:/02_CloudCTL.md
[03 VFW Firewall & Gateway		- LXD Container]:/03_Gateway.md
[04 DNS & DHCP Service			- OCI Podman Container]:/04_Dnsmasq.md
[05 Application Router Proxy	- OCI Podman Container]:/05_HAProxy.md
[06 Simple Artifact Server		- OCI Podman Container]:/06_Nginx.md
[07 TFTP Boot Artifact Server	- OCI Podman Container]:/07_Tftpd.md
[08 Deploy OpenShift Red Hat CoreOS Nodes]:/08_DeployNodes.md
