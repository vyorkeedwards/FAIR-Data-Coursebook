---
title: Publish and preserve
teaching: 10
exercises: 15
---

::::::::::::::::: questions

- What is Data Archiving?
- What are Data Repositories?
- What is a DOI, and why is it important?

::::::::::::::::::::::

:::::::::::::::: objectives

- The participant will understand the importance of archiving datasets on trusted data repositories.
- The participant will learn the significance of the Digital Object Identifier (DOI).

::::::::::::::::::

## FAIR principles used in Data Archiving  
**Findable**   
FM-F1A (Identifier Uniqueness) → [doi.org/10.25504/FAIRsharing.r49beq](https://doi.org/10.25504/FAIRsharing.r49beq)  
FM-F3 (Resource Identifier in Metadata) → [doi.org/10.25504/FAIRsharing.o8TYnW](https://doi.org/10.25504/FAIRsharing.o8TYnW)  

**Accessible**  
FM-A2 (Metadata Longevity) → [doi.org/10.25504/FAIRsharing.A2W4nz](https://doi.org/10.25504/FAIRsharing.A2W4nz)  


### 1. What is Data Archiving?

'Data Archiving' is the practice of placing a digital source in a preservation phase, i.e., the long-term storage of research data. 

The various academic journals have different policies regarding how much of their data and methods researchers are required to store in a public archive. Similarly, the major grant-giving institutions have varying attitudes toward public archival of data. In general, publications must have attached sufficient information to allow fellow researchers to replicate and test the research.

### 2. What are Data Repositories?

Datasets are archived in **Data repositories**. They are storage locations for digital objects. **Data repositories** can help make a researcher's data more discoverable by search engines (e.g., Google) and ultimately lead to potential reuse. Therefore, using storage can lead to increased citations of your work. Data repositories can also serve as backups during rare events where data are lost to the researcher and must be retrieved.

## Note
Data Archiving is the long-term storage of research data.
Data repositories can help make research data more discoverable by search engines (e.g., Googlebots). 

Examples of data repositories:

| Data Repository | About |
|---|---|
|[DataverseNL](https://dataverse.nl/dataverse) | DataverseNL is a community-specific repository that focuses on Dutch universities and research centers.|
|[4TU Data](https://data.4tu.nl/) | 4TU Data is a community repository that was originally created by three technical universities in the Netherlands.|
|[PANGEA](https://pangaea.de/) | PANGEA is a community-specific repository that focuses on Earth & Environmental Science.| 
|[FigShare](https://figshare.com/) | FigShare is an open generic data repository for general purposes; it can store data and other digital objects.| 

Just like FigShare, many data repositories are for general use. They provide a low entry barrier to making data **Findable**, addressing FM-F1A (Identifier Uniqueness) and FM-F3 (Resource Identifier in Metadata). 


## Recommendations for general-purpose data repositories
[ZENODO](https://zenodo.org/) administrated by [CERN](https://home.cern/)  
[SURF Repository](https://repository.surfsara.nl/) administrated by [SURF](https://www.surf.nl/)  
[DataverseNL](https://dataverse.nl/)  administrated by [DANS](https://dans.knaw.nl/en/)

Quick characteristics of general-purpose repositories:  

- Safe — your research is stored safely for the future in a Data Centre for as long as CERN and/or DANS exist.
- Citeable — every upload is assigned a Digital Object Identifier (DOI) to make them citable and trackable.
- No waiting time — Uploads are made available online as soon as you hit publish, and your DOI is registered within seconds.
- Open or closed — Share, e.g., anonymized clinical trial data with only medical professionals via our restricted access mode.
- Versioning — Easily update your dataset with our versioning feature.
- GitHub integration — Easily preserve your GitHub repository in Zenodo.
- Usage statistics — All uploads display standards-compliant usage statistics.

![](https://datamanagement.hms.harvard.edu/sites/g/files/mcu941/files/assets/Images/2020-12-10-Repo-Matrix.png){alt="Harvard Medical School, RDM - Data Repositories"}
Image: Harvard Medical School, RDM - Data Repositories. Accessed Jul-2022 - *datamanagement.hms.harvard.edu/share/data-repositories*

#### [Original Harvard Dataverse](https://dataverse.harvard.edu/dataverse/harvard)

## Some public registries where you can find lists of trusted repositories for Data Archiving 
**Registry of Research Data Repositories (re3data)**  → [re3data.org//](https://www.re3data.org/)  
**PLOS ONE Recommended Repositories**  → [journals.plos.org/plosone/s/recommended-repositories](https://journals.plos.org/plosone/s/recommended-repositories)  
**NIH Recommended Repositories:**  → [sharing.nih.gov/repositories-for-sharing-scientific-data](https://sharing.nih.gov/data-management-and-sharing-policy/sharing-scientific-data/repositories-for-sharing-scientific-data)  
**Nature - Scientific Data Guidelines:**  → [nature-com.mu.idm.oclc.org/sdata/policies/repositories](https://www-nature-com.mu.idm.oclc.org/sdata/policies/repositories)  
**OpenDOAR - Directory of Open Access Repositories**  →  [v2.sherpa.ac.uk/opendoar/](https://v2.sherpa.ac.uk/opendoar/)


:::::::::::::::::::: challenge

Dataverse

Go to **[dataverse.org](https://dataverse.org/)** and scroll down until you see a map. Respond to the following:  

1. How many installations of Dataverse are there?  
2. How many Dataverse installations are in the Netherlands?  
3. DataverseNL is the data repository hosted by DANS. It supports all higher education institutions in the Netherlands. How many datasets exist now in DataverseNL? (Aug 2022)   

::::::::::::::::::: solution

1. There are 83 installations worldwide. This means that 83 organizations have a copy of the original Harvard Dataverse layout and have hosted it on their own servers to support researchers.  
2. There are 3 installations in the Netherlands: DataverseNL, IISH Dataverse, and NIOZ Dataverse.
3. There are 6,075.

::::::::::::::::
:::::::::::::::::::

### 3. What is a DOI, and why is it important?

The DOI is a common identifier used for academic, professional, and governmental information such as articles, datasets, reports, and other supplemental information. The [International DOI Foundation (IDF)](https://www.doi.org/) is the agency that oversees DOIs. [CrossRef](https://www.crossref.org/) and [DataCite](https://datacite.org/) are two prominent not-for-profit registries that provide services to create or mint DOIs. Both have membership models where their clients are able to mint DOIs distinguished by their prefix. For example, DataCite features a [statistics page](https://stats.datacite.org/) where you can see registrations by members.

A DOI has three main parts:

- Proxy or DOI resolver service
- Prefix which is unique to the registrant or member
- Suffix, a unique identifier assigned locally by the registrant to an object

![](https://authorcarpentry.github.io/CODATA-RDA-Trieste-2016/Figure1.jpg){alt="Digital Object Anatomy" width=800 height=400}

In the example above, the prefix is used by the Australian National Data Service (ANDS), now called the Australia Research Data Commons (ARDC), and the suffix is a unique identifier for an object at Griffith University. DataCite provides DOI [display guidance](https://support.datacite.org/docs/datacite-doi-display-guidelines) so that they are easy to recognize and use, for both humans and machines.

::::::::::::: challenge

Upload a dataset in the [DEMO DataverseNL](https://demo.dataverse.nl/) repository.

Download the following mock dataset: [MOCK DATA](../data/MOCK_DATA_BOOTCAMP.xlsx).  

What is the DOI of your dataset?

::::::::::::::: solution

There is no one single answer 🤓

:::::::::::::::::
:::::::::::::::::

::::::::::::: discussion  

Archiving Scenario

You are a researcher of Migration studies, and you conducted personal interviews. So naturally, you want your research data to be visible in your community, given the impact on the topic. Still, obviously, you can't upload the transcripts, not even in a restricted form, since it's an ethnographic study.  

Discuss with your team how it would be best to handle data archiving in situations like this type of data. 

::::::::::::::::::::

:::::::::::::::::: keypoints

- **Data repositories** can make research data more discoverable by machines (e.g., Google search engine).
- Always aim for a repository that fits your community (e.g., DataverseNL). Else, deposit your dataset on generic repositories (e.g., Zenodo).
- If the data is about human subjects or includes demographics, you can always choose to make it private or deposit an aggregated subset.

::::::::::::::::::::::
