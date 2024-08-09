---
title: Infrastructure standards
description: >
   A list of infrastructure standards at Dorset HealthCare
created: 2020-06-29
lastUpdated: 2024-08-09 14:30:00
author: Andrew Harrison
---

# Infrastructure standards

## Common standards

These standards apply to all types of IT infrastructure.

## Security and privacy by design and default

All infrastructure must be built and maintained in observance of [the principles of data protection by design and default](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/accountability-and-governance/guide-to-accountability-and-governance/accountability-and-governance/data-protection-by-design-and-default/).

## Alignment with national architecture principles

We align where possible with the [NHS national architecture principles](https://digital.nhs.uk/developer/architecture/principles) and the [CDDO technology code of practice](https://www.gov.uk/guidance/the-technology-code-of-practice).

## Cloud First

Our preference is to use cloud or virtual infrastructure over physical infrastructure for new workloads.

Architectural approval MUST be sought before committing to any workload that requires new physical infrastructure.

When deploying cloud infrastructure, the following general approach must be followed: SaaS is preferred over PaaS over IaaS.

Cloud infrastructure MUST either belong to a vendor who will provide ongoing support and maintenance of the infrastructure for the whole life of the contract
_or_ it must use the Trust's Microsoft Azure cloud infrastructure.

Where the Trust's cloud infrastructure is used, it will be subject to our development, support and documentation standards.

## All infrastructure must be updatable

The Trust expects that security updates shall be applied, and vulnerabilities addressed within set timescales and in accordance with policy. The Trust will not support the purchase or operation of IT systems that cannot be routinely or easily updated.

## All infrastructure must have vendor or 3rd-party support

It will not be permitted to have infrastructure that has no support from the manufacturer, vendor or an appointed third party.

## Other Standards

* [Hosting standard](infrastructure/hosting/readme)
* [Cloud Infrastructure](infrastructure/cloud/readme)
* [Physical Infrastructure (on-premise, data-centre)](infrastructure/physical/readme)
* [Network Infrastructure](infrastructure/networks)
