# Learning Microsoft Defender for Cloud

> Previously known as Microsoft Security Center or Azure Security Portal

## What is MSFT Defender for Cloud

- cloud-native application protection platform (CNAPP)
- security posture management, measures and practices versus cyber threats / vulnerabilities
- multi-cloud solution for workload protection (Azure, AWS, GCP)
- shared responsibility model

### Benefits

- As a development security operations (DevSecOps) solution, unifies security management at the code level across multicloud and multi-pipeline environments
- As a cloud security posture management (CSPM) solution...
  - provides VISIBILITY and GUIDANCE
  - assesses resources, subscriptions, organizations
  - identifies actions to prevent breaches
  - provides single score based on aggregating findings
  
- As a cloud workload protection platform (CWP or CWPP) solution...
  - protection for servers, containers, storage, databases, and other workloads
    > protection provideed through enhanced security feature plans
  - powered by Micosoft Threat Intelligence

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
  - a signle score in reference to current security posture
  - the higher the score, the lower the risk level
- Recommendations provided
  - customized and prioritized tasks to immprove security posture
  - remediation steps included
  > `Fix` button may be available for automated implementations
- Governance 
  - view and assign ownership of recommendations to drive remediation


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
  - App Service
  - SQL databases
  - SQL servers on machines
  - open-source relational databases
  - Azure Cosmos DB
  - Storage
  - Containers
  - AI Services
  - Key Vault
  - Resource mMnager
  - DNS

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
> Sentinel, other Defender products like _Defender for Endpoint_, and third-party SIEM tool logs / alerts can fully integrate here as well

### Workload protections

- Continuosly Assess
  - understand your current security posture
- Secure
  - harden the connected services / resources
- Defend
  - detect _and_ resolve threats to services / resources

### Cloud Security explorer

### Workbooks

- Numerous different reports users can run
> For example, Vulnerability Assessment

## Items needing to be moved to proper place:
- integrates with Azure Policy
- leverages Azure Security Benchmark
- cross-cloud and on-premises scenarios
- _Enhanced security_ feature available
- CVE = Common Vulnerabilities and Exposure

## Beneficial Certifications

- SC-900
- AZ-500
