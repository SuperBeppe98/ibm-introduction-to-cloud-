[Back to Syllabus](./README.md#course-syllabus)

## Learning Objectives
- Describe the key __Components of Cloud Infrastructure__
- Explain __Virtualization__
- List the features and benefits of __VM__
- List the features and benefits of __Bare Netal Servers__ and how they differ from virtual servers
- Describe how to build a __Secure Cloud Networking Presence__
- Explain how __Contain-Based Technology__ works
<br>

## Overview of Cloud Infrastructure
- __Cloud Region__
    - a geographic area or location where a Cloud provider’s infrastructure is clustered
    - isolated from each other so that Cloud operations in other Regions would keep running even if impacted by a natural disaster.
    - e.g. NA South or US East
- __Availability Zones__ _(AZ)_
    - Each Cloud Region can have multiple AZ
    - typically distinct Data Centers with their own power, cooling and networking resources.
    - connected to other AZs using very high bandwidth network connectivity.
    - e.g. DAL-09 or us-east-1
- __Cloud Data center__
    - a huge room containing cloud infrastructure<p><img src="https://user-images.githubusercontent.com/60066472/85117106-48b6e280-b259-11ea-96d1-4b8f18752f79.PNG" width="500"></p>
- __Compute Options__
    - Virtual Servers (VMs): software-based
    - Bare Metal Servers: physical servers (not virtualized)
    - Serverless : abstraction layer on top of virtual machines
- __Storage Options__: Block, File, Object
- __Networking Options__: routers, switchs, security groups, ACLs, VLANs, VPCs, VPNs, firewalls, load balancers, gateways, traffic analyzers, CDNs
<br>

## Virtualization and Virtual Machines Explained
- __Virtualization__
    - the process of creating a software based, or virtual, version of something,
- __Hypervisors__
    - manages the resources that are allocated to VMs.
    - Type1(Bare Metal): VMware, ESXi, or Microsoft Hyper-v, or even open-source KVM
    - Type2(Hosted): Oracle, VirtualBox, or VMware Workstation
- __VM__
    - a software based computer, run like a physical computer
    - can run multiple of VMs on a hypervisor<p><img src="https://user-images.githubusercontent.com/60066472/85118840-d267af80-b25b-11ea-8251-f73c2c6142a8.PNG" width="500"></p>
- __Advantages__: cost-saving, agility & speed, less downtime
<br>

## Types of Virtual Machines
- __Virtual Machines__
    - Also called as...: Virtual Servers, Virtual Instances, Instances
    - User Options: Region and Zone, OS, Multi or Single-tenant, Billing Hourly or Monthly
- __Shared or Public Cloud VMs__
    - Underlying physical server is virtualized and is shared
    - Also offer custom configurations<p><img src="https://user-images.githubusercontent.com/60066472/85119549-e6f87780-b25c-11ea-9bda-e28160f6e26f.PNG" width="400"></p>
- __Transient or Spot VMs__
    - take advantage of unused capacity in a cloud data center
    - much lower cost than regular VMs of similar sizes
    - risk of losing these VMs when capacity in the data center decreases
- __Reserved Virtual Server Instances__
    - allow you to reserve capacity and guarantee resources for future deployments.
    - useful when you know you require at least a certain level of cloud capacity
for a specific duration.
- __Dedicated Host__
    - run on a given host so they can make exclusive use of full capacity and resources
    - typically used for meeting compliance and regulatory requirements or meet specific licensing terms.
<br>

## Bare Metal Servers
- __Bare Metal Server__
    - a single-tenant, dedicated physical server.
    - providers will fix if anything goes wrong with the hardware or rack connection
    - customers are responsible for administering and managing everything else on the server.
    - both preconfigured / custom-configured possible
- __Characteristics__
    - may take longer to provision than virtual servers
    - tend to be more expensive 
    - not all providers provide bare metal servers
    - fulfil the demanding needs of high-performance computing (HPC) and data intense applications that require
“minimal latency-related delays”
        - workload examples: ERP, CRM, AI, Deep Learning, and Virtualization.
    - High degrees of Security Controls<p><img src="https://user-images.githubusercontent.com/60066472/85121007-05f80900-b25f-11ea-99f2-05ed1eebcfb6.PNG" width="400"></p>
<br>

## Secure Cloud Networking
- __Secure Network__
    - building a cloud network vs deploying a network in an on-premises data center<p><img src="https://user-images.githubusercontent.com/60066472/85121199-58392a00-b25f-11ea-96f7-af851fbf025b.PNG" width="400"></p>
    - how to build a secure cloud networking presence<p><img src="https://user-images.githubusercontent.com/60066472/85121536-e6151500-b25f-11ea-969d-f5e9a2409699.PNG" width="400"></p>
<br>

## Containers
- __Containers__
    - an executable unit of software 
    - application code is packaged, along with its libraries and dependencies
    - can be run anywhere, whether it be on desktop, traditional IT, or the cloud.
    - small, fast, and portable,
    - do not need to include a guest OS in every instance and unlike virtual machines <p><img src="https://user-images.githubusercontent.com/60066472/85122251-380a6a80-b261-11ea-962c-b7bf821b59ac.PNG" width="400"></p>
<br>

## Module Summary
- Cloud infrastructure consists of data centers, storage, networking components, and compute resources.
- Virtualization is the process of creating a software-based version of physical resources, made possible through the use of hypervisors. 
- A few different types of Virtual Machines can be provisioned on the cloud. These include:
    - Shared or Public Cloud VMs that are provider-managed, multi-tenant deployments that can be provisioned on-demand with predefined sizes
    - Transient or Spot VMs that take advantage of unused capacity in a cloud data center
    - Reserved VMs that allow you to reserve capacity and guarantee resources for future deployments 
    - Dedicated hosts that offer single-tenant isolation
- Bare metal servers are single-tenant physical servers that are dedicated to a single customer. Bare metal servers fulfil the demanding needs of high-performance computing (HPC) and data intense applications and are ideal for applications that have a high degree of security or compliance requirements.
- Networking capabilities in the cloud are delivered as a service rather than in the form of rack-mounted devices. Cloud resources, such as VMs (or VSIs), storage, network connectivity, and load balancers, are deployed into subnets within Virtual Private Clouds (VPCs). Using private and public subnets allows users to deploy multi-tier enterprise applications securely. Load balancers distribute the traffic and allow applications to be responsive.
- Containers are an executable unit of software in which application code is packaged, along with its libraries and dependencies, in common ways so that it can be run anywhere—desktops, traditional IT, or the cloud. Containers are lighter weight and consume fewer resources than Virtual Machines - helping streamline the development and deployment of cloud native applications.
<br>


[Go to Next Module](./5_Storage_and_Content_Delivery_Networks.md)
