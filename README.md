# Learning Microsoft Defender for Cloud

> Previously known as Microsoft Security Center or Azure Security Portal

## What is MSFT Defender for Cloud

- cloud-native application protection platform (CNAPP)
- security measures and practices versus cyber threats / vulnerabilities
- multi-cloud solution (Azure, AWS, GCP)
- shared responsibility model

### Benefits

- As a development security operations (DevSecOps) solution, unifies security management at the code level across multicloud and multi-pipeline environments
- As a cloud security posture management (CSPM) solution, identifies actions to prevent breaches
- As a cloud workload protection platform (CWPP) solution, protection for servers, containers, storage, databases, and other workloads

### Overview

- Provides unified view into security posture
- Includes independent cloud secureity pillars:
  - Security posture
  - Regulatory compliance
  - Workload protections
  - Inventory

#### Security posture

- An assessment of environment's overall security posture
- Secure score
- Recommendations provided
- Governance - view and assign ownership of recommendations to drive remediation


#### Regulatory compliance

### Setup

- Connect different environments to Defender for Cloud:
  - Azure (eligible subscriptions are onboarded)
  - AWS
  - GCP
  - additional environments:
    - Azure DevOps
    - GitHub
    - GitLab
    - DockerHub
    - Jfrog
- Explore security coverage plans:
  - Defender CSPM
  - Servers
  - App service
  - SQL databases
  - SQL servers on machines
  - open-source relational databases
  - Azure Cosmos DB
  - Storage
  - Containers
  - AI Services
  - Key vault
  - Resource manager

### Recommendations

- Set owners and due dates for recommendation remediation implementation
- Exemptions can be made for entire recommendations
  > Exemptions can be made through disable rules as well.  
  > Exempted resources appear as not applicable and do not affect secure score
- It is possible to trigger Logic apps
- Deny rules for future misconfigured resources

### Security alerts

- You can view all affected resources that contributed to generating an alert
- Recommendations for remediation are available:
  - point-in-time remediation
  - preventing future attacks as well
- Automated flows with logic apps
- Email notifications
> Sentinel and other Defender products like *Defender for Endpoint* logs / alerts can fully integrate here as well

### Workload protections

### Cloud Security explorer

### Workbooks

- Numerous different reports users can run
> For example, Vulnerability Assessment

## Items needing to be moved to proper place:
- integrates with Azure Policy
- leverages Azure Security Benchmark
- cross-cloud and on-premises scenarios
- *Enhanced security* feature available
- CVE = Common Vulnerabilities and Exposure

## Beneficial Certifications

- AZ-500
- SC-900