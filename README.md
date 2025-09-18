#### Library Main Navigation: &nbsp; &nbsp;  <b> [Ecosystem Library Home](https://github.com/NIH-NICHD-Ecosystem) </b> &nbsp; | &nbsp;[User Stories](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/README.md) &nbsp; | &nbsp; [Efforts](https://github.com/NIH-NICHD-Ecosystem/Efforts/blob/main/README.md) &nbsp; | &nbsp; [Library Help](https://github.com/NIH-NICHD-Ecosystem/LibraryHelp/blob/main/README.md)
</br><br/>
# E4: Data Governance Metadata Schema


### A metadata schema for annotating data governance information to inform decisions about data handling across the data lifecycle, including appropriate data linking, sharing, access, and use.

<br/>

# Table of Contents

- [Effort Overview](#effort-overview)
- [Effort Documentation](#effort-documentation)
- [User Stories](#user-stories)
<br/><br/>

# Effort Overview 

The _Eunice Kennedy Shriver_ National Institute for Child Health and Human Development (NICHD) Office of Data Science and Sharing (ODSS) is leading an effort to develop frameworks and tools to support responsible individual-level record linkage for research with NICHD populations. The Data Governance Metadata Schema structures and describes dataset-level data governance information from a variety of sources, referred to as policies (e.g., data use agreements, consents, laws, and institutional review board (IRB) determinations), and enables annotation of rules from each policy (e.g., permission to link the dataset, prohibition on re-identification, and obligation to obtain approval to access the dataset). Rules can also have constraints or conditions (e.g., dataset can only be accessed in a protected enclave, dataset must be de-identified using a specific method before sharing), and the parties that those rules apply to. The schema is based on the [Open Digital Rights Language (ODRL) Information Model](https://www.w3.org/TR/odrl-model) and includes a Data Governance Profile of data governance specific terms and definitions that extend ODRL.

The motivation for developing the schema was to streamline decisions among data providers, data repository stewards, researchers, and other stakeholders regarding whether two or more datasets can be linked and how linked data can be shared and used. The schema can also be used to develop solutions for reusing and/or integrating existing data from multiple sources while adhering to data governance for each dataset in a variety of settings.  For example, the collection and analysis of standardized data governance information can support the determination of appropriate use of generative AI applications with certain datasets.  It can also support determination of whether and how data can move between discrete systems.

#### Primary contact:  _[NICHDecosystem@nih.gov](mailto:NICHDecosystem@nih.gov)_<br/>

#### Details: 
* <b> Created and maintained by:</b> NICHD ODSS in collaboration with The MITRE Corporation </br>
* <b> NIH contacts:</b>
    * Rebecca Rosen, Director, NICHD ODSS
    * Valerie Cotton, Deputy Director, NICHD ODSS
    * Elizabeth Clerkin, Data Science and Sharing Specialist, NICHD ODSS 

<br/><br/>

# Effort Documentation
All documentation can be found in the [Data Governance Metadata Schema User Guide](https://github.com/NIH-NICHD/Data-Linkage-Governance/tree/main/MetadataSchema) and the overall [Data Linkage Governance Metadata Project page](https://github.com/NIH-NICHD/Data-Linkage-Governance/tree/main).

# User Stories


The following User Stories motivated and informed this Effort:

| S#  | User Story | Current Problem | User Goal |
|----|----|----|-----|
|44| [As a researcher, I want to access, link, share, and use data from multiple research and administrative data sources (such as CDC NHANES, SAMHSA NSDUH, NIH/NIDA MTF, and ACF AFCARS) so I can study the effects of COVID-19 pandemic on mental health of children and determine whether related outcomes are more severe for children in foster care. ](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-44.md)</li></ul> | Each dataset is subject to different rules often stored as unstructured narrative text within policy documents, data use agreements, consent forms, laws, and other sources of governance information. It’s difficult to extract this information and understand how these rules intersect. | My goal is to understand whether certain datasets can be linked, and if so, what rules and controls apply to the resulting linked dataset so I can appropriately share and use the linked data to study pediatric COVID|
|45| [As a researcher, I want to access, link, share, and use data from multiple research and administrative data sources (such as NIH/NCI NCCR, CMS T-MSIS, and ACF AFCARS) so I can study the impact of COVID-19 infection of COVID-19 infection on pediatric cancer survivors and the impact of COVID-19 infection on future pediatric cancer outcomes. ](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-45.md)</li></ul> | Each dataset is subject to different rules often stored as unstructured narrative text within policy documents, data use agreements, consent forms, laws, and other sources of governance information. It’s difficult to extract this information and understand how these rules intersect. | My goal is to understand whether certain datasets can be linked, and if so, what rules and controls apply to the resulting linked dataset so I can appropriately share and use the linked data to study pediatric COVID|
|46| [As a researcher, I want to access, link, share, and use data from multiple research and administrative data sources (such as NIH/NCATS N3C, PCORnet, NIH RADx, and EPA Air Quality) so I can study whether SARS-CoV-2 vaccination results in reduced asthma-related school absences at 3/6/12+ months post-vaccination. ](https://github.com/NIH-NICHD-Ecosystem/UserStories/blob/main/stories/storyID-46.md)</li></ul> | Each dataset is subject to different rules often stored as unstructured narrative text within policy documents, data use agreements, consent forms, laws, and other sources of governance information. It’s difficult to extract this information and understand how these rules intersect. | My goal is to understand whether certain datasets can be linked, and if so, what rules and controls apply to the resulting linked dataset so I can appropriately share and use the linked data to study pediatric COVID|

<br/>
