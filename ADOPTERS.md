# OVN-Kubernetes Adopters

This page contains a list of organizations/companies and projects/products who use OVN-Kubernetes as adopters in different usage levels (development, beta, production, GA etc...).

**NOTE:** For adding your organization/company and project/product to this table (alphabetical order), fork the repository and open a PR with the required change. See the list of adopter types at the bottom of this page. Say hi on Slack too!

## Adopters
| Organization/Company/Project | Usage level | Adopter type | Details |
| --- | --- | --- | --- |
| Internet Initiative Japan Inc. | Production | end users (non CNCF member) | Uses OVN-Kubernetes in their on-premise Kubernetes platform |
| KubeStellar Console | Beta / Development | Another project | Provides a guided install mission for OVN-Kubernetes via an open-source Kubernetes dashboard with AI-assisted operations |
| Nutanix / Flow CNI | Production | Service Provider | Builds Flow CNI on OVN-Kubernetes, integrated with Nutanix Flow and VPC networking |
| NVIDIA | Production | End-User (CNCF member) | Uses OVN-Kubernetes in their production environments |
| Red Hat, Inc. / OpenShift | Production | Service Provider | Uses OVN-Kubernetes as their default CNI in OpenShift product |
| SAIC Motor Corp. Ltd | Production | end users (non CNCF member) | Uses OVN-Kubernetes as a networking solution to build a multi-tenant private cloud |
| Submariner | Production | Another project | Uses OVN-Kubernetes CNI for Multicluster Networking |

## Adopter Types
See [CNCF definition of an adopter](https://github.com/cncf/toc/blob/main/FAQ.md#what-is-the-definition-of-an-adopter)

Any single company can fall under several categories at once in which case it should enumerate all that apply and only be listed once
- **End-User (CNCF member)** - Companies and organizations who are End-User members of the CNCF. 
- **Another project** - An open source project that leverages a CNCF project as part of their solution, integrates with for compatibility and interoperability, or is used in the supply chain of another project. 
- **end users (non CNCF member)** - Companies and organizations that are not CNCF End-User members that use the project and cloud native technologies internally, or build upon a cloud native open source project but do not sell the cloud native project externally as a service offering (those are Service Providers). This group is identified in the written form by the convention *end user*, uncapitalized and unhyphenated. 
- **Service Provider** - A Service Provider is an organization that repackages an open source project as a core component of a service offering, sells cloud native services externally. A Service Provider's customers are considered transitive adopters and should be excluded from identification within the `ADOPTERS.md` file.
- **Consultancy** - An entity whose purpose is to assist other organizations in developing a solution leveraging cloud native technology. They may be embedded in the end user team and is responsible for the execution of the service. Service Providers may also provide consultancy services, they may also package cloud native technologies for reuse as part of their offerings. These function as proxies for an end user. 