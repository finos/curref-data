[![FINOS - Incubating](https://cdn.jsdelivr.net/gh/finos/contrib-toolbox@master/images/badge-incubating.svg)](https://finosfoundation.atlassian.net/wiki/display/FINOS/Incubating)

<img src="https://github.com/finos/branding/blob/master/project-logos/active-project-logos/currency-reference-data/2022_CRD_Logo_Horizontal.jpg" width="250">


# Currency Reference Data Project

# Overview
[Collaborating on a Model and Data Standard](https://www.youtube.com/watch?v=aIpYLu4PrLs&list=PLbzoR-pLrL6qpva7J9joOU5Nvx_A_ax_L&index=28) -- Presentation by Vijayesh Chandel & Elaine Fraser, Goldman Sachs & Sailesh Pandey, Nomura, at the [October 2021 Open Source Strategy Forum](https://events.linuxfoundation.org/open-source-strategy-forum/) in London.

# Roadmap
The objective of this project is to create a standard object to represent currency data and create a central cloud based repository of the currency data. 
Modeling is being done in the FINOS hosted instance of [Legend Studio](https://github.com/finos/legend-studio), and the current model can be accessed at https://legend.finos.org/studio/viewer/UAT-38 (see screenshot below) Please note that you will need to have an account on the FINOS hosted instance of Legend Studio in order to access it. You can request an account at [finos.org/legend](https://www.finos.org/legend). 

<img src="https://github.com/finos/curref-data/blob/master/project-resources/CurRefModel_Screenshot.png" width="1000">

## Stage 1 - Planning - completed
- [x] Agree on concept with participants and define a currency object
- [x] Collate use cases to identify participants who want to get involved e.g. reg reporting
- [x] Feasibility analysis – to get a view of commitment needed from participants
- [x] Finos Technologies/Open Data Store – requirements review
- [x] Milestone – WG to agree on plan for initiative
- [x] Timeline – Aug 2020 to end of September 2020 (4 sessions)

## Stage 2 – Design (Part 1: Model) - completed
- [x] Design of a standardised agnostic currency ref data model using example data sets, Legend Studio
- [x] Initial focus on currency and commodities to formulate design
- [x] Milestone – to agree on the model and sign off from the Cur Ref Data working group
- [x] Timeline – October 2020 to end of December 2020 (6 sessions)

## Stage 3 – Design (Part 2: Workflow)
- [ ] Design of workflow – conflict resolutions, updating of data, API etc - 
- [ ] Model & data versioning
- [ ] Define model governance
- [ ] Milestone – to agree on the workflow design and submit it for build
- [ ] Timeline – by end of September 2021 

## Stage 4 - Build
- [ ] Confirm the model with ISO before publishing it into PROD
- [ ] Build and Testing (bandwidth TBC by Sailesh)
- [ ] Milestone – to have a working data retrieval from the cloud
- [ ] Timeline –  TBC 

## Background

The Currency Reference Data project spawned off the [Legend Pilot FX Options working group](https://github.com/finos/legend#phase-1-january-2020---september-2020---completed), which identified the need to standardise currency data for several use cases. The ISO Currency code data will be the baseline set of records and attributes which will be enriched with additional attributes and eventually with additional rows for non-ISO currencies and precious metals.  The benefit to the industry would be a single shared source of this reference data that is managed by a group of industry participants.

[<img src="https://user-images.githubusercontent.com/51138318/113764904-9833a580-96e9-11eb-9301-aab8cfb07f81.png" width="300">](https://www.iso.org/iso-4217-currency-codes.html)

In an example of cross pollination across FINOS projects, the FX Options working group connected with the Securities Reference Data project and participants from both groups decided to set up a Currency Reference Data work stream under the FINOS [Securities Reference Data project](https://github.com/finos/secref-data). In August 2021, Currency Reference Data was [proposed](https://github.com/finos/community/issues/136) and contributed by Goldman Sachs and Nomura as a standalone FINOS project. For Currency Reference Data materials and meeting minutes prior to August 2021, please see the Currency Reference Data [archive](https://github.com/finos/secref-data/issues?q=label%3A%22Currency+Reference+Data%22+).  

# Get Involved: Contribute to CurRef Data
There are several ways to contribute to Currency Reference Data:

* **Join the next meeting**: participants of the Currency Reference Data workstream meet monthly on the third Tuesday at 10am ET / 3pm GMT. Find the next meeting on the [FINOS projects calendar](https://calendar.google.com/calendar/u/0/embed?src=finos.org_fac8mo1rfc6ehscg0d80fi8jig@group.calendar.google.com&ctz=America/New_York) and browse [past meeting minutes in GitHub](https://github.com/finos/secref-data/labels/meeting).
* **Join the mailing list**: Communications for the Currency Reference Data project are conducted through the currency-ref-data@finos.org mailing list. Please email [currency-ref-data@finos.org](mailto:currency-ref-data@finos.org) to join the mailing list.
* **Propose changes to the model**: request an account on the FINOS Legend Studio hosted instance at [finos.org/legend](https://www.finos.org/legend) in order to access the model at https://legend.finos.org/studio/viewer/UAT-38
* **Contribute use cases** at https://github.com/finos/secref-data/issues/30
* **Raise an issue**: if you have any questions or suggestions, please [raise an issue](https://github.com/finos/curref-data/issues/new/choose)

# Governance: Community Specification

## What is the Community Specification For?

The Community Specification process is a repository-based approach for creating standards and specifications in version control systems, such as Git. 

## What is the benefit?

The Community Specification allows you to start a specification development effort as easily as an open source project.  The Community Specification incorporates the terms and processes required for standards and specification development, including legal terms, intellectual property issues, due process, and governance.  It also provides the mechanisms to allow your project to grow and scale.  For example, the Community Specification provides the basis to take your specification to other standards bodies, including international standards bodies, for formal standardization if your community desires to pursue those options.

## How to get started?

Instructions for using the Community Specification are included in the [..Getting Started.md](https://github.com/finos/curref-data/blob/master/governance-documents/..Getting%20Started.md) file.

## Could I just use an open source license for my specifications? Why should I use a specification license?

Open source is collaboration around a specific codebase, while specifications provide a blueprint developers implement in different ways in many different codebases. Accordingly, open source licenses provide terms to use and modify a particular codebase and specification licenses are designed to provide terms for separate independent implementations of the specification. Because of this, if you use an open source license for specifications, people implementing those specifications may be doing so without the meaningful copyright or patent grants that you expect.

A second difference is that common open source software and specification licenses tend to have different coverage scopes for intellectual property terms. Open source licenses generally grant terms scoped only to a contributor's contributions. Specification licenses, however, generally cover implementations of the entire specification, regardless of who made the actual contribution. Because the specification will often be developed with contributions from multiple organizations, the various contributing organizations will often want to review and approve the full specification before extending patent commitments to the final, combined result. 

## Who developed the Community Specification

The Community Specification has been developed via the [Joint Development Foundation](http://www.jointdevelopment.org), with inspiration from the [Open Web Foundation agreements](http://openwebfoundation.org) and the [Alliance for Open Media Patent License 1.0](http://aomedia.org/license/patent-license/).


