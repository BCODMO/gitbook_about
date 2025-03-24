# About

## Introduction

The Biological and Chemical Oceanography Data Management Office (BCO-DMO) is a trustworthy, publicly accessible, domain science data repository created to curate, publish, and archive digital data and information from biological, chemical, and biogeochemical research conducted in coastal, marine, Great Lakes, and laboratory environments. The office provides services that span the full data life cycle, from data management planning support and DOI creation, to archive with appropriate long-term facilities. Repository staff work closely with investigators to help them prepare, publish, and share their data and related information for reuse.

Views and opinions expressed by BCO-DMO belong solely to the project PIs and its team members, and do not necessarily reflect those of project funders.

## History

BCO-DMO was established in 2006 through a collaborative merging of two legacy data management offices created in support of the US oceanographic research programs: the Joint Global Ocean Flux Study (JGOFS) and US Global Ocean Ecosystem Dynamics Research (GLOBEC). Although these programs have sunsetted, the repository continues to support the data-sharing needs of the broader ocean ecosystem research community today. The office is physically located in Woods Hole, Massachusetts at the Village Campus of the Woods Hole Oceanographic Institution, where it has cultivated close ties with the scientific community.

## Mission & Vision&#x20;

The BCO-DMO project strives to stay apprised of evolving and leading practices, and continually innovates on information management technology to ensure that the data curated is as FAIR as possible, and that our system is intuitive for all users. We seek to support the process of conducting open and transparent oceanographic research; not only by relieving researchers from the difficult aspects of data management and data sharing, but by providing a rich resource of high-quality oceanographic data and information for reuse through an easy-to-use web-based system. These goals and objectives drive our mission and underpin our vision.

**Mission:&#x20;**_**To work closely with oceanographic researchers to organize, describe, and share their science output, while curating a rich repository of research-ready marine-related data for use in science, policy and management, and educational efforts.**_

**Vision:&#x20;**_**An unparalleled data catalog of well-documented, interoperable oceanographic data and information, accessible to all end-users through an intuitive web-based interface for the purposes of advancing marine research, education, and policy.**_

## Operations & Infrastructure

BCO-DMO centers its technical infrastructure around a knowledge graph of Resource Description Framework (RDF) resources that describe data and metadata objects. APIs and queryable interfaces are layered on top of the knowledge graph to power data access tools, website content, and other user interfaces. This strategy helps remove dependencies on any one particular software stack for data and metadata to be collected, and thereby provides BCO-DMO with the flexibility to replace software components in its architecture without impacting the underlying data model. The knowledge graph is stored in an open-source Virtuoso RDF triplestore.

The website is powered by Drupal with additional access to data provided through an ERDDAP server. ERDDAP ([Environmental Research Division’s Data Access Program](https://coastwatch.pfeg.noaa.gov/erddap/information.html)) is an open, widely-used tool developed by NOAA to provide a simple, consistent way to download subsets of scientific datasets in common file formats, and make graphs and maps. BCO-DMO is currently developing its ERDDAP server to replace its historic JGOFS Data Server (the genesis of the OpenDAP protocol), so users may notice this transition. Elasticsearch is used to power all search capabilities on the BCO-DMO website. Redis serves as our cache server for improving API and query performance.

All BCO-DMO software is deployed using Docker, and all custom software development is managed in Github ([https://github.com/BCODMO/](https://github.com/BCODMO/), please be aware that some repositories are marked private on Github for security reasons).

## Partnerships

### Funder Partnerships

BCO-DMO is able to provide its services through generous support from the US National Science Foundation Oceanography Division’s Biological and Chemical Sections and the Division of Polar Programs’ Antarctic Organisms & Ecosystems, and is the designated data repository for investigators funded through these programs. Current funding is provided by NSF grant [OCE-2421145](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2421145). Previous awards include: [OCE-1924618](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1924618\&HistoricalAwards=false), [OCE-1435578](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1435578), [OCE-1031253](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1031253), and [OCE-0646353](https://www.nsf.gov/awardsearch/showAward?AWD_ID=0646353). The office also receives support from other organizations for targeted activities, and works with investigators funded from alternate (e.g., private, local governmental) sources on a fee-for-service basis.

Parameter and ontology work has been supported by the [Gordon and Betty Moore Foundation](https://www.moore.org/).

<figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

### **Data Infrastructure Partnerships**

The BCO-DMO repository was certified as a trusted repository through CoreTrustSeal in 2019. [CoreTrustSeal](https://www.coretrustseal.org/) is an independent, international, non-profit organization promoting trustworthy data infrastructure. Certification involves assessment and review of 16 different requirements intended to demonstrate the robustness and sustainability of a repository’s infrastructure, thereby ensuring that the data managed by the repository can be shared, preserved, and reused over long timeframes.

Ensured preservation of the BCO-DMO data catalog is achieved through its partnerships with the National Centers for Environmental Information ([NCEI](https://www.ncei.noaa.gov/)) and the Marine Biological Laboratory and Woods Hole Oceanographic Institution ([MBLWHOI](https://www.mbl.edu/research/mblwhoi-library)) Library. These organizations receive copies of finalized published data packages for long-term curation which are versioned as necessary.

BCO-DMO is a member of the [World Data System](https://worlddatasystem.org/) and is recognized as an Associate Data Unit under the International Oceanographic Data and Information Exchange ( [IODE](https://iode.org/about/community/)). BCO-DMO is also a founding member of the U.S. [Council of Data Facilities](https://www.esipfed.org/collaboration-areas/council-of-data-facilities-cdf/).

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

### Project Collaborations

Through collaborative partnerships that bridge science and cyberinfrastructure, BCO-DMO is able to help researchers address their data-related challenges or educate their communities. The office has worked with the ocean proteomics community on the NSF EarthCube Ocean Protein Portal; promoted reuse of oceanographic biogeochemical data through the BIOS High Dive into Ocean Data project; and collaborated with Ocean Carbon and Biogeochemistry (OCB) community on efforts such as development of phytoplankton taxonomy reporting best practices, and coordination of global marine time series data through the Marine Ecological Time Series (METS) Research Coordination Network. Within the cyberinfrastructure community, the office was instrumental in development of Science on Schema.org through the NSF EarthCube P418 project.

### **Education & Outreach Collaborations**

Members of the BCO-DMO team are trained [Data Carpentry](https://datacarpentry.org/) instructors and the office offers training in data wrangling, as well as how to access and manipulate BCO-DMO data using automated workflows within scripting and coding languages. In addition, BCO-DMO partners with external projects to develop data management best practices curriculum.

