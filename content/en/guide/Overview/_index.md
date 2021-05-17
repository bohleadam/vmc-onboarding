---
title: "Overview"
linkTitle: "Overview"
weight: 1
date: 2020-05-06
description: >
  Overview of the on-boarding process for your VMware Cloud on AWS SDDC (Software Defined Datacenter)
---

{{% pageinfo %}}
This guide is not a replacement for <a href="https://docs.vmware.com/en/VMware-Cloud-on-AWS/index.html" target="_blank">Offical VMware documentation</a> , this is only meant to complement the offical documenation as a helpful reference. When in doubt refer to offical documentation or contact VMware Support.
{{% /pageinfo %}}

## VMware Cloud on AWS Overview

![VMC Overview](https://vmc-onboarding-images.s3-us-west-2.amazonaws.com/Overview/vmwonawsoverview.png)

## Key terms and concepts

- VPC - Virtual Priate Cloud
- VPN - Virtual Priave Network
- VIF -Virtual Interface
- DX - Amazon Direct Connect
- BGP - Border Gateway Protocol

## Who you need to complete on-boarding

VMware Cloud on AWS has a lot of moving parts. You will need the following people unless you are all these roles:  

* **vSphere Admin**: Someone at your organization with administrative access to vCenter and vmc.vmware.com
* **Network Admin**: Someone at your organization that can configure routers, switches and provide IP addresses
* **AWS Admin**: Someone at your organization that can manages your AWS account and can create VPCs and subnets and run cloud formation templates and if needed request and configure Direct connect. Optionally this person could also grant you the rights in AWS per your security guidelines.

This guide is broken up into 4 phases:

* [1. On-Boarding your SDDC](/guide/1.-on-boarding-sddc/): Step by step guide to get your SDDC deployed
* [2. Connecting your SDDC](/guide/2.-Connect-SDDC/): Get your SDDC connected to your data center
* [3. Configuring your SDDC](/guide/3.-Configure-SDDC/): Get your SDDC setup and running
* [4. Deploying Add-Ons](/guide/4.-Deploy-Add-Ons/): Quickly install Site Recovery Manager and Hybrid Cloud Connect
