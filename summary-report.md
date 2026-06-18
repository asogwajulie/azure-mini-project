# Azure Mini Project Summary

## Selected Azure Region
The selected region for this deployment is South Africa North.
This region was chosen because it is the closest Azure region to Nigeria, which helps to reduce network latency and improve response time for deployed services. Selecting a geographically closer region ensures better performance, especially for applications that may be accessed by users within West and Southern Africa.

Another important consideration in region selection is service availability and compliance. Not all Azure services are available in every region, so choosing South Africa North ensures access to a wide range of Azure services while still maintaining proximity to the user base.
Overall, this region provides a balance of performance, availability, and reliability for the project.

# Shared Responsibility Model (Storage Account)

The Shared Responsibility Model defines how security and management responsibilities are divided between the cloud provider and the customer.

For the deployed Azure Storage Account, responsibilities are shared as follows:

- Microsoft’s Responsibilities

Microsoft is responsible for:
Physical security of datacenters
Hardware maintenance and replacement
Network infrastructure and connectivity
Underlying platform availability and resilience
Managing the Azure cloud infrastructure that hosts the Storage Account

= User's Responsibilities
Users are responsible for:
Configuring secure access to the storage account
Managing Identity and Access Management (IAM) using role-based access control (RBAC)
Protecting data through proper access keys or Azure Active Directory authentication
Ensuring secure configuration (e.g., disabling public access where not needed)
Monitoring usage and managing cost control
Managing data lifecycle (upload, delete, backup strategies if needed)

# Azure Resource Group and Resource Overview

All resources in this project were deployed within a Resource Group, which acts as a logical container for managing Azure resources.
The primary resource deployed is:
Azure Storage Account
The Storage Account is used for storing and managing data objects such as blobs, files, and tables depending on configuration. It serves as a scalable and secure cloud storage solution within the Azure ecosystem.

# Cost Management and Azure Free Tier
This project was deployed using the Azure Free Tier, which provides limited free usage of selected services.
To avoid unexpected charges, the following practices are important:
Monitoring resource usage through the Azure Cost Management dashboard
Avoiding unnecessary resource creation or idle services
Setting up budget alerts where applicable
Deleting unused resources after testing
Understanding cost management is essential in cloud computing because most Azure services operate on a pay-as-you-go model.

# Security Considerations
Security is a key part of any Azure deployment. In this project, the following security principles apply:
Multi-Factor Authentication (MFA) is recommended for account protection
Role-Based Access Control (RBAC) is used to restrict access to resources
Storage accounts are secured using access keys or Azure Active Directory authentication
Data encryption is enabled by default for data at rest
Secure configuration practices are followed to minimize exposure
These measures help ensure that cloud resources remain protected from unauthorized access.

# Conclusion
This project provided hands-on experience with core Azure concepts, including region selection, availability zones, shared responsibility, resource organization, and cost management.
It also reinforced the importance of designing cloud solutions that prioritize performance, security, and cost efficiency. Understanding these foundational concepts is essential for building scalable and reliable cloud-based systems.
## Selected Region
I selected South Africa North because it is geographically closest to Nigeria and provides lower latency.

## Availability Zones
Availability Zones improve redundancy and fault tolerance by distributing services across separate datacenters.

