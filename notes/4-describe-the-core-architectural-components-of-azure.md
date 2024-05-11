# Describe the core architectural components of Azure

After completing this module, you’ll be able to:

    Describe Azure regions, region pairs, and sovereign regions.
    Describe Availability Zones.
    Describe Azure datacenters.
    Describe Azure resources and Resource Groups.
    Describe subscriptions.
    Describe management groups.
    Describe the hierarchy of resource groups, subscriptions, and management groups.

## What is Microsoft Azure?

Azure is a continually expanding set of cloud services that help you meet current and future business challenges.

### What does Azure offer?

Limitless innovation. Build intelligent apps and solutions with advanced technology, tools, and services to take your business to the next level.

  * Bring ideas to life. Build on a trusted platform to advance your organization with industry leading AI and cloud services.
  * Seamlessly unify. Efficiently manage all your infrastructure, data, analytics, and AI solutions across an integrated platform.
  * Innovate on trust. Rely on trusted technology from a partner who's dedicated to security and responsibility.

### What can I do with Azure?

Azure provides more than 100 services that enable you to do everything from running your existing applications on virtual machines to exploring new software paradigms, such as intelligent bots and mixed reality.

For example, Azure provides artificial intelligence and machine-learning services that can naturally communicate with your users through vision, hearing and speech. 

It also provides storage solutions that dynamically grow to accomodate massive amounts of data.

Azure services enables solutions that aren't feasible without the power of the cloud.

## Get started with Azure accounts

To create and use Azure services, you need an Azure subscription. 

![Azure subscription and resources](https://learn.microsoft.com/en-us/training/wwl-azure/describe-core-architectural-components-of-azure/media/account-scope-levels-9ceb3abd.png)

## Using the Learn sandbox

Another way to interact is with the Azure CLI interactive mode. This changes CLI behavior to more closely resemble an integrated development environment (IDE).

Interactive mode provides autocompletion, command descriptions, and even examples.

Enter az interactive to enter interactive mode.

```ps
az interactive
```

## Describe Azure physical infrastructure

### Physical infrastructure

The physical infrastructure for Azure starts with datacenters. Conceptually, datacenters are the same as large corporate datacenters. They're facilities with resources arranged in racks, with dedicated power, cooling and networking infrastructure.

As a global cloud provider, Azure has datacenters around the world. However, these individual datacenters aren't directly accessible.

Datacenters are grouped into Azure Regions or Azure Availability Zones that are designed to help you achieve resiliency and reliability for your business-critical workloads.

The Global Infrastructure site can be used to view the infrastructure: https://datacenters.microsoft.com/globe/explore

#### Regions

A region is a geographical area on the planted that contains at least one, but potentially multiple datacenters that are nearby and networked together with a low-latency network. Azure intelligently assigns and controls the resources within each region to ensure workloads are appropriately balanced.

When you deploy a resource in Azure, you'll often need to choose the region where you want your resource to be deployed.


Some services or virtual machine (VM) features are only available in certain regions, such as specific VM sizes or storage types. 

There are also some global Azure services that don't require you to select a particular region, such as Microsoft Entra ID, Azure Traffic Manager, and Azure DNS.

#### Availability zones

Availability zones are physically separate datacenters within an Azure region.

Each availability zone is made up of one or more datacenters equipped with independent power, cooling and networking. 

An availability zones is set up to be an isolation boundary. If one zone goes down, the other continues working. 

Availability zones are connected through high-speed, private fiber-optic cables.

To ensure resiliency, a minimum of three seperate availability zones are present in all availability zone-enabled regions. Not all Azure regions support availability zones.

