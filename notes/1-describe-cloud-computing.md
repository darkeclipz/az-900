# 1. Describe Cloud Computing

  * Microsoft Azure is a *cloud computing platform*.
  * What is a **cloud**? A system that delivers IT services over the internet.
  * Azure service supports: simple web services, fully virtualized computers, remote storage, database hosting, centralized account management, artificial intelligence and IoT services.

**AZ-900 Domain Area**

 * Describe cloud concepts.
 * Describe Azure architecture and services.
 * Describe Azure management and governance.

## What is Cloud Computing?

 * **Cloud computing** is the delivery of computing services over the internet.
 * Computing services include:
   * Common IT infrastructure: virtual machines, storage, databases, and networking.
   * Internet of Things (IoT), machine learning (ML), and artificial intelligence (AI) infrastructure.
 * Because cloud computing uses the internet to deliver these services, it doesn't have to be constraint by physical infrastructure the same way that a traditional datacenter is. You can rapidly scale your IT infrastructure.
 * You only have to pay for the services you use.
 * The basic services that all cloud providers deliver are *compute power* and *storage*.
 * Cloud providers manage the upkeep of the computer, ensure there a back ups and that the operating system is up to date, as well as making sure that everything is up an running 24/7.

## Describe the shared responsibility model

  * The **shared responsibility model** informs who is responsible for what, depending on the cloud service type.
  * There are three cloud services types:
    * infrastructure as a service (**IaaS**)
    * platform as a service (**PaaS**)
    * software as a service (**SaaS**)
  * Traditionally, with a on-premise datacenter, the customer is responsibility for everything. This includes physical hardware, networking, keeping operating systems up to date and managing software.
  * When using a cloud provider you are always responsible for: the information and data stored in the cloud, devices that are allowed to connect to your cloud, and the accounts and identities of people, services and devices within your organization.
  * The cloud provider is always responsible for: the physical data center, the physical network, and the physical hosts.
  * The service model determines responsibility for: operating systems, network controls, applications, identity and infrastructure.

The following diagram highlights how the shared responsibility model informs who is responsible for what, depending on the cloud service type.

![Shared responsibility model diagram](https://learn.microsoft.com/en-us/training/wwl-azure/describe-cloud-compute/media/shared-responsibility-b3829bfe.svg)

## Define cloud models

  * The **cloud model** define the deployment type of cloud resources. The three main cloud models are: private, public, and hybrid.
  * A **private cloud**, is in some way, the natural evolution of the corporate datacenter. It's a cloud that's used by a single entity. It comes at a greater cost and fewer of the benefits of a public cloud deployment. A private cloud may be hosten by your on site datacenter, a dedicated datacenter off site, or a third party that has a dedicated datacenter to your company.
  * A **public cloud** is built, controlled, and maintained by a third-party cloud provider. With a public cloud, anyone that wants to purchase cloud services can access and use resources. The general public availability is a key difference between a public and private cloud.
  * A **hybrid cloud** is a computing environment that uses both public and private clouds in an inter-connected environment. It can be used for a private cloud to surge for increased, temporary demands by deploying public cloud resources. Hybrid clouds can be used to provide an extra layer of security.

The following table highlights a few key comparitive aspects between the cloud models.

|Public cloud|Private cloud|Hybrid cloud|
|--|--|--|
|No capital expenditures to scale up.|Organizations have complete control over resources and security.|Provides the most flexibility.|
|Applications can be quickly provisioned and deprovisioned.|Data is not collocated with other organizations' data.|Organizations determine where to run their applications.|
|Organizations pay only for what they use.|Hardware must be purchased for startup and maintenance.|Organizations control security, compliance, or legal requirements.|
|Organizations don't have complete control over resources and security.|Organizations are responsible for hardware maintenance and updates.||

  * **Multi-cloud**: In a multi-cloud scenario you use multiple public cloud providers.
  * **Azure Arc**: Azure Arc is a set of technologies that helps manage your cloud environment. Azure Arc can help manage your cloud environment, whether it's a public cloud solely on Azure, a private cloud in your datacenter, a hybrid configuration, or even a multi-cloud environment.
  * **Azure VMware Solution**: If you have already established with VMware in your private cloud but want to migrate to a public or hybrid cloud? Azure VMware Solution lets you run your VMware workloads in Azure with seamless integration and scalability.

## Describe the consumption-based model

  * When comparing IT infrastructure models, there are two types of expenses to consider:
    * **Capital expenditure** (CapEx): is typically a one-time, up-front expenditure to purchase or secure tangible resources.
    * **Operation expenditure** (OpEx): is spending moeny on services or products over time.
  * Cloud computing falls under OpEx because cloud computing operates on a **consumption-based model**. You don't pay for the physical infrastructure, electricity, or anything else with maintaining a data center. Instead, you only pay for the resources that you use. If you don't use any IT resources this month, you don't pay for any IT resources.
 * Benefits of the consumption-based model:
   * No upfront costs.
   * No need to purchase and manage costly infrastructure.
   * The ability to pay for more resources when they are needed.
   * The ability to stop paying for resources that are no longer needed.
 * Cloud computing is the delivery of computing services over the internet by using a pay-as-you-go pricing model.