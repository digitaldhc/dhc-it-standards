---
title: Hosting standard
description: >
   The hosting standard at Dorset HealthCare
created: 2024-08-09
lastUpdated: 2024-08-09
author: Andrew Harrison
---

# Hosting standard

## Background

The [government’s cloud-first policy](https://www.gov.uk/guidance/government-cloud-first-policy), as well as the [NHS digital architecture principles](https://digital.nhs.uk/developer/architecture/principles) both state that digital services should be delivered from the public cloud unless there is a clear reason not to do so. A formal and structured adoption of public cloud technologies can help the organisation: 

* deploy digital workloads more quickly and flexibly; 
* improve the availability and resilience of digital workloads; 
* reduce the attack surface of digital workloads; 
* store data more securely; 
* deliver better value to the organisation by allowing staff to spend less time on maintenance and support of lower level infrastructure. 

## Our approach to new workloads

At Dorset HealthCare, our preference will be for new workloads to be hosted remotely, or in the cloud. This means that newly procured applications must be delivered in remote or cloud infrastructure that is the responsibility of the supplier for the whole life of the contract. While the Trust will continue to provide on-premise “Wintel” hosting for its existing and legacy applications, this capability will be slowly wound down and architectural approval will be required for any new application that requires “infrastructure as a service” or on-premise hosting.  

Where application and data workloads are developed in-house, they should by default be built to take advantage of the “platform as a service” capabilities of the Trust’s cloud environment(s) to enable early leverage of the benefits described above, only falling back to “infrastructure as a service” or on-premise hosting with sufficient justification. 

### Our hosting order of preference for new workloads

| Hosting order of preference        | Externally contracted systems | Internally developed systems |
| ---------------------------------- | ----------------------------- | ---------------------------- |
| Software as a Service (SaaS)       | 1                             |                              |
| Remote hosting                     | 2                             |                              |
| Platform as a Service (PaaS)       | 3                             | 1                            |
| Infrastructure as a Service (IaaS) | 4                             | 2                            |
| On-premise hosting                 | 5                             | 3                            |

## Our approach to existing workloads

Existing workloads continue to be supported in their current locations. However, where the Trust continues to provide on-premise "Wintel" hosting we will move this away from being provided directly on the Trust's own premises in favour of colocated datacentre space, procured under the Crown Commercial Service framework [RM6262 - Crown Hosting II](https://www.crowncommercial.gov.uk/agreements/RM6262).

This approach ensures that the Trust's on-premise compute is provided from purpose built, geographically separated datacentres located within high security campus settings, suitable for the hosting of critical national infrastructure at any security classification and at all HMG threat levels, at advantageous rates and powered by hedged and green-sourced electricity. Crown Hosting is a [Technology Code of Practice](https://www.gov.uk/guidance/the-technology-code-of-practice) compliant route to digital transformation and for the migration of IT service to the public cloud, and benefits from a central Crown Commercial Service team who act on behalf of all customers to manage commercial matters and undertake security and technical assurance, along with service and performance management.

Moving our workloads to Crown Hosting frees Dorset HealthCare from the liabilities of our local data rooms and allows the Digital Services Group to offer the organisation a higher level of assurance of our hosting arrangements than we would be able to achieve on our own premises. 
