---
title: Publish and preserve
teaching: 10
exercises: 15
---

::::::::::::::::: questions

- What is data archiving?
- What are data repositories?
- What is a DOI, and why is it important?

::::::::::::::::::::::

:::::::::::::::: objectives

- Understand the role of trusted repositories in long-term preservation.
- Learn why repositories improve discovery and citation.
- Understand how DOI supports persistence and citation.

::::::::::::::::::

> **FAIR principles used in Data Archiving**  
> **Findable**
> FM-F1A (Identifier Uniqueness) → [doi.org/10.25504/FAIRsharing.r49beq](https://doi.org/10.25504/FAIRsharing.r49beq)  
. FM-F3 (Resource Identifier in Metadata) → [doi.org/10.25504/FAIRsharing.o8TYnW](https://doi.org/10.25504/FAIRsharing.o8TYnW)  
>
> **Accessible**  
> FM-A2 (Metadata Longevity) → [doi.org/10.25504/FAIRsharing.A2W4nz](https://doi.org/10.25504/FAIRsharing.A2W4nz)  


## 1. What is data archiving?

Data archiving is the long-term preservation of research data and related digital objects.

Funders and journals increasingly expect enough of the data and methods to be preserved so that results can be inspected, understood, and, where possible, replicated.

## 2. What are data repositories?

Data repositories are storage locations for digital objects such as datasets, code, supplementary files, and metadata.

Repositories make research outputs easier to find and can also provide:

- preservation
- backup
- citation infrastructure
- versioning
- controlled access options

Examples of data repositories:

| Data Repository | About |
|---|---|
|[DataverseNL](https://dataverse.nl/dataverse) | Community repository supporting Dutch universities and research centres |
|[PANGEA](https://pangaea.de/) | Domain repository for Earth and environmental sciences | 
|[FigShare](https://figshare.com/) | General-purpose repository for many digital object types | 

### General repository recommendations

Check the guidance from your institution. Otherwise, aim for a domain-specific or community repository where possible. Registries such as <https://www.re3data.org/> can help you to find one.

If there isn't an appropriate domain-specific or community repository, a trusted general repository is usually better than leaving data only on a local drive or project website.

- Zenodo: <https://zenodo.org/>
- Figshare: <https://figshare.com/>
- Harvard Dataverse (instance of Dataverse available to all researchers): <https://dataverse.harvard.edu/>

Typical strengths of general-purpose repositories include:

- persistent identifiers
- rapid publication
- versioning
- backup and preservation
- usage statistics
- open or restricted access modes

Additional registries that help identify suitable repositories:

- re3data: <https://www.re3data.org/>
- PLOS recommended repositories:
  <https://journals.plos.org/plosone/s/recommended-repositories>
- NIH repositories guidance:
  <https://sharing.nih.gov/data-management-and-sharing-policy/sharing-scientific-data/repositories-for-sharing-scientific-data>
- OpenDOAR: <https://v2.sherpa.ac.uk/opendoar/>


:::::::::::::::::::: challenge

Dataverse

Visit <https://dataverse.org/> and scroll down to the map of Dataverse installations
1. How many installations of Dataverse are there?
2. Are there any in the UK?
3. There is a link to a page of metrics. What's the most common subject area of data deposited across the Dataverse?
The Harvard Dataverse Installation is open to researchers around the world. Navigate to its website.
4. How many datasets does it contain?

::::::::::::::::::: solution

1. This changes over time (150 on 15th October 2026)
2. None!
3. Arts and Humanities
4. This changes over time (305,529 on 15th October 2026)

::::::::::::::::
:::::::::::::::::::

### 3. What is a DOI, and why is it important?

DOI is a persistent identifier commonly used for articles, datasets, reports, and other scholarly outputs.

Two major DOI registration services in research are:

- Crossref: <https://www.crossref.org/>
- DataCite: <https://datacite.org/>

Repositories and journals usually register scholarly outputs for DOIs as an automatic part of the publication process.

A DOI has three conceptual parts:

- the resolver service
- the registrant prefix
- the locally assigned suffix

![Diagram explaining DOI structure](https://authorcarpentry.github.io/CODATA-RDA-Trieste-2016/Figure1.jpg){alt='Illustration of DOI components'}

DOIs make resources easier to cite and track, and they continue resolving even when storage details change. 

::::::::::::: discussion  

Archiving Scenario

You conducted personal interviews for an ethnographic migration study. The raw transcripts cannot be openly shared, even under restricted access.

How should archiving be handled in this case? What metadata, derived outputs, or access statements should still be preserved and published?

::::::::::::::::::::

:::::::::::::::::: keypoints

- Repositories improve preservation, discovery, and citation.
- Prefer a trusted community repository when one fits your discipline.
- General repositories such as Zenodo still provide a strong baseline for FAIR publication.
- DOI is a key persistent identifier for datasets and publications.

::::::::::::::::::::::
