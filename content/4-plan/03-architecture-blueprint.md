---
title: "Architecture Blueprint"
metaTitle: "Architecture Blueprint | WP"
metaDescription: "This describes the architectural representation of the system's components. At the inception, it could be the implementation of a feature vertical and the setup of the needed infrastructure to act as a guideline for further development."
published: true
documentation: "TechArchitecture"
metaTags:
  - Plan
  - Architecture Blueprint
  - Winning Product 
---


## Why
Modern-day applications use sophisticated technical resources such as Load balancers, Queues, Data Stores, and containerized components. While there are many technical options to choose from, selecting the right resource for the right reason is crucial. The selection might depend on the throughput, security or even cost aspects. Still, the important thing is there has to be a rationale for the selection based on your requirements.

Once the architecture blueprint is in place, it will then act as a reference for future development. The technical decisions are already made at this point. The developers will just have to follow this design without much of a hassle. Architecture blueprint also acts as a communication mechanism to any technology interested stakeholder regarding the technology stack in use.


## How
Consider the following aspects when establishing a technical architecture.

- Configurability
Despite your awareness of requirements, some assumptions likely have to be made when building the initial product architecture. Good architects can build the system in a highly configurable manner, so if some of the components are changed, later on, it has a minimum dependency on the rest of the system. It will help to postpone some of the architectural decisions until there is enough information. So make your architecture configurable to make changes later on hassle-free.

- Non-functional requirements
Your architecture must support all required non-functional requirements, such as performance and security. It is recommended to analyze the capability here before starting to implement any features.

- Extendability
Both functional and non-functional requirements are bound to scale up as the business grows. It is usually a sign of a growing business. Your architecture should support extendability in all aspects.

- Infrastructure As Code 
Infrastructure As Code (IaC) enables system administrators to automate the configuration and provisioning process thereby it reduces human errors and saves time. Following configuration orchestration and management tools can be used to implement Infrastructure as Code and help you automate your infrastructure.
- Terraform
- AWS CloudFormation
- Azure Resource Manager and Google Cloud Deployment Manager
- Chef
- Puppet
- Saltstack
- Ansible
- Docker
- Vagrant


## References
- [Infrastructure as code](https://en.wikipedia.org/wiki/Infrastructure_as_code)
- [IaS](https://www.plutora.com/blog/infrastructure-as-code)
- [Infrastructure as Code tools](https://www.thorntech.com/2018/04/15-infrastructure-as-code-tools/)
