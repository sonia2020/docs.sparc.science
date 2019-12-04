---
title: "Frequently Asked Questions"
keywords: documentation, faq
sidebar: sparc_sidebar
toc: false
permalink: faq.html
summary: This document is intended to serve to share questions and interactions between the cores and users that may serve as FAQs
folder: general
---

### What is a SPARC data set?
A SPARC data set is a collection of data files, supporting documents, and metadata produced by a SPARC investigator.  According to the SPARC data sharing policy, a data set should include any data or supporting materials that the PI deems necessary for a 3rd party to reuse the data and reproduce or replicate the results. In general, such files may include raw (primary) data, experimental protocols, analysis code/workflows, processed (derivative) data, complete results, and textual descriptions of the datasets and their contents.  At time of submission by a PI, the dataset may be considered complete (that is, no new data will will be collected), or it may represent a batch or slice of data that is part of a larger dataset being collected over several milestones.

### What is the difference between the SPARC data model and metadata on the DAT-CORE? 
The Data Standards Committee and MAP-CORE have created a common data model to cover SPARC data. The UCSD curation team is curating submitted data according to that data model, which will be transfered to the DAT-Core.  PI’s are free to add their own meta data to their datasets utilizing the tools available in the DAT-Core to organize their data for their own purposes, but they do not need to specifically for the SPARC data model. It is however important to correctly include the CSV files for the BIDS Structure.

### How do I know how to structure my files for SPARC?
SPARC has developed a standard file structure for organizing and naming files, inspired by the BIDS (Brain Imaging Data Structure).  Instructions and examples are available. NOTE: Tabular data should be saved as .CSV files to make sure data is readable without the need for Microsoft Office.

### Is the readme file necessary?
Yes, please create the file and keep it in your main folder; it may be a placeholder, i.e., a blank text file; however if there are notes that you have about the experiment that do not fit please put them here.

### Why do I have to follow the SPARC file structure?
The SPARC file structure is based on BIDS, an extensible standard developed for organizing data and metadata for neuroimaging, but which is also applicable to other domains.  SPARC is currently evaluating how far BIDS can be extended to cover the data types and workflows used in SPARC, but it should be employed where possible.  The BIDS standards has been endorsed by the International Neuroinformatics Coordinating Facility as fulfilling the requirements for a community standard that can and should be widely adopted across neuroscience.  The use of community standards is a key pillar of FAIR.  The benefits for SPARC for using a structured file structure are as follows:
It will be easy for another researcher to work on your data. To understand the organization of the files and their format you will only need to refer them to the SPARC documentation. This is important not only for consumers of SPARC data, but in your own lab as well (“Future you”).  By using the SPARC file structure you will save time trying to understand and reuse data acquired by a graduate student or postdoc that has already left the lab.
As an accepted community standard, there is a growing number of data analysis software packages that can understand data organized according to BIDS thereby increasing the usability of your data.  
Databases such as OpenNeuro.org, LORIS, COINS, XNAT, SciTran and others will accept and export datasets organized according to BIDS. Thus, SPARC data can be combined more easily with data accruing in other projects.
Validation tools can be developed that can automatically check dataset integrity and let you and the curation team easily spot missing values.

### Where can I find help on uploading my protocol to protocols.io?   
We’ve provided a brief tutorial [here](https://docs.google.com/presentation/d/1WhoLvOVRIbCzu3x30Dd0O1cC09ZGT4g0IFOf4Eq7yfI/edit).  Please note this document changes a little as we get questions to improve readability,  More information is available on the protocols.io website.  eggrg

### I tried to join the SPARC group in protocols.io, but I can’t find it?
The SPARC group is private so you need to be added as a member.  Anita Bandrowski is the administrator.  Please send her a message at her protocols.io user account: [https://www.protocols.io/researchers/anita-bandrowski](https://www.protocols.io/researchers/anita-bandrowski), including the email address you used to set up the protocols account.

### How do I upload large data to the DAT-CORE?
Large file upload (10GB and greater) is now supported using the web-application, as well as using the Blackfynn Agent. More information can be found elswhere on this website.

### Who do I contact at the DAT-CORE if I need support or assistance uploading my data?
For all support questions about the platform, feedback, or bug reports, please use the “Get Help” button after logging into the platform to send the DAT-CORE a message. This is the best method to reach the DAT-CORE support and development team, and will be prioritized within Blackfynn to guarantee a quick response. For more general questions about the SPARC effort, and the role of the DAT-Core, please contact Leonardo Guercio or Joost Wagenaar by email or Slack (using the SPARC Slack account).

### Once the data and protocol are made public after the embargo period, will I still be able to publish papers using these data and protocol?  i.e., do journals consider release of data and protocols to be prior publication?
SPARC takes the position, consistent with stated policies on data sharing and preprint deposition of publishers and journals, that release of data through the SPARC Data Portal and deposition of associated protocols in protocols.io does not preclude a researcher from publishing works that utilize or further describe either the data or the protocol. Publishers and journals are actively behind data sharing and many are either requiring or recommending that data be made available in a public repository at time of publication.  Authors are to include a data availability statement that includes the DOI or URL of the data set deposited. Publishers and many journals have made explicit statements stating that deposition of a manuscript in a preprint service like biorXiv does not constitute prior publication. We agree with protocols.io that making the protocol available through protocols.io ahead of publication is covered under that policy and will not interfere with submission of any articles utilizing such protocols.
