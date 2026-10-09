---
title: Introduction
teaching: 10
exercises: 5
---

:::::::::::::::::::::: questions

- Does FAIR data mean open data?
- What are Digital Objects and Persistent Identifiers?
- What kinds of persistent identifiers are commonly used?

::::::::::::::::::::::

::::::::::::::::::::::::: objectives

- Understand that FAIR does not simply mean open.
- Explain the difference between human-readable and machine-friendly digital objects.
- Recognize DOI as one type of PID used to identify digital objects.

:::::::::::::::::::::::::

## 1. Does FAIR data mean open data?

No.    
FAIR means that data and related research objects are designed to be easy for humans and machines to find, understand, access, and reuse. Some FAIR data can also be open, but openness and FAIRness are not the same thing. Sometimes data cannot be shared openly (for example where it is health data relating to individual patients), but it can be made FAIR.

![](fig/FAIRcoursebook-image0_1.png){alt="Diagram showing a mixture of text and icons with the message: When you do Research Data Management (RDM) following the FAIR Principles you aim to Open Science. Open not in the sense of Open Datasets but open in the sense of Transparent and Accessible Science" style="max-width: 80%; height: auto;"}

### What does it mean to be machine-readable vs human-friendly?  

Human-readable content is easy for a person to inspect directly, but that does not guarantee that software can parse and reuse it automatically (for example, pdfs of scans of text can be very readable to a human, but very difficult for a machine to process). Machine readable content uses explicit structure, such as CSV, JSON, or XML, so a computer can interpret relationships and values without guessing.

During this lesson, "machine-friendly" is used broadly to mean material that is machine-readable and also supports further automated action and interoperability.

![](fig/FAIRcoursebook-image0_2.png){alt="Diagram showing that FAIR equals Friendly DOs (Digital Objects) such as Data, Metadata, Code, Software and Protocols and is Human and Machine Friendly"}

## 2. What are Digital Objects and Persistent Identifiers?

A **Digital Object** is a bit sequence located in a digital memory or storage that has informational value on its own. For example:  

- A scientific publication
- A dataset
- A rich metadata file
- A README file describing access and reuse conditions

A **Persistent Identifier**, or PID, is a durable reference to a digital or physical resource. PIDs are backed by technical infrastructure and governance arrangements that help them continue resolving even when the resource itself changes location.

Common uses of PIDs include those identifying:

- articles, datasets, and software
- researchers
- organizations and funders
- projects and instruments
- physical samples and media objects

DOI is one well-known PID type and is commonly used for datasets and publications. ORCID is another example, focused on researcher identity.

For a short explainer of the importance of PIDs, see the [FREYA project video](https://en.wikipedia.org/wiki/File:FREYA-The-power-of-PIDs-V05-1.webm)

:::::::::::::::: challenge

### arXiv

arXiv is a preprint repository for physics, math, computer science, and related disciplines. It allows researchers to share and access their work before it is formally published. 

Visit the arXiv new papers page for [Machine Learning](https://arxiv.org/list/cs.LG/recent). 
Pick a paper, open its PDF, and search for `http` or `doi`.

What kinds of links do the authors use for data or software references, and why is a DOI usually more robust than a personal website or repository link alone?
 
:::::::::::::: solution

Authors often link to GitHub repositories, project pages, or other web pages for software and data. Those locations may move or disappear over time. A DOI is more robust because it resolves through persistent infrastructure and points to current metadata about the object even if the storage location changes.

::::::::::::::::::::::::::
:::::::::::::::::::::::::

:::::::::::::::::::::::::::: discussion

### How does your discipline share data?

How does your discipline usually share data? Is there a data journal, domain repository, or another community-specific mechanism for making research outputs findable and reusable? 

For example, the American Astronomical Society (AAS), via the publisher IOP Physics, offers a [supplement series](https://iopscience.iop.org/journal/0067-0049/page/article-data) as a way for astronomers to publish data. 

::::::::::::::::::::::::::::

:::::::::::::::::::::::: keypoints

- FAIR means making research objects more usable by humans and machines, not automatically making them open.
- Machine-friendly objects are structured so software can interpret and reuse them reliably.
- Digital objects include datasets, publications, metadata records, and related documentation.
- DOI is a common PID used for datasets and publications.

::::::::::::::::::::::::


