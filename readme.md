![Adoption flag](https://img.shields.io/badge/Adoption%20state-Unadopted-blue) ![Document flag](https://img.shields.io/badge/Document%20state-Draft-blue)

# Dorset HealthCare IT standards

Welcome to the [Dorset HealthCare](https://www.dorsethealthcare.nhs.uk/) IT standards internet homepage. These standards are written in Markdown and managed as code, and inspired by a similar set of standards in use at [NHS England](https://github.com/nhsengland/it-standards).

Our standards are built to relate to the operational requirements of the organisation as well as existing best practice, standards and policies across the public sector.

## List of standards

The list of currently published standards is as follows:

* Applications
    * [Email integration](./applications/email-integration.md)
* Identity
    * [Identity](./identity/)
* Infrastructure
    * [Common infrastructure standards](./Infrastructure/)
    * [Hosting standard](./Infrastructure/hosting/)
    * [Physical infrastructure standards (datacentre and on-prem)](./Infrastructure/physical/)
    * [Physical infrastructure standards (hardware type approval)](./Infrastructure/physical/type-approval.md)
* Security
    * [Cloud applications and services guidance](./security/cloud-tools.MD)

## How to contribute

* Please raise an [issue](https://github.com/digitaldhc/dhc-it-standards/issues)
* Standards owner: andrew.harrison11 (at) nhs.net

Contributions from known individuals will be accepted via a pull request. Create a branch in this repository, make changes there and then submit a pull request to get the changes approved and migrated into the *main* branch which will always be the current and published version.

Minor changes will be reviewed informally, more major changes will be reviewed by the [Infrastructure Technical Design Authority (internal link).](https://nhs.sharepoint.com/sites/msteams_9eaf40/SitePages/Infrastructure-technical-design-authority.aspx)

## Principles for the development of these standards
We open source our standards and develop and publish them on Github. This promotes openness in the NHS technical community and allows other organisations to fork these standards to use as the basis for their own should they wish to do this under the terms of the Open Government Licence ([see below](#copyright-and-licence)). Because our standards are published on the internet we must always take care to ensure they do not contain detailed or confidential technical information, credentials, secrets and so on. In our publication of our standards on the internet we are following precedents established by organisations such as [NHS England](https://nhsengland.github.io/it-standards/#/) and the [Ministry of Justice](https://security-guidance.service.justice.gov.uk/).

## Format and structure

This repository uses [GitHub flavoured markdown](https://github.github.com/gfm/). Diagrams can be included as code and rendered on the GitHub website using [Mermaid.](https://github.blog/developer-skills/github/include-diagrams-markdown-files-mermaid/)

## Copyright and licence

All documentation in the repository is subject to [Crown Copyright](https://www.nationalarchives.gov.uk/information-management/re-using-public-sector-information/uk-government-licensing-framework/crown-copyright/) and is licensed under the [Open Government Licence version 3](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).

All code in the repository is licenced under the MIT licence.