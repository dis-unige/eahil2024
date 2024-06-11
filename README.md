# Librarians’ quest to exhaustivity and openness: tracking institutional publications and observing evolving trends in data sharing

Research presented at the EAHIL conference 2024 - 11–14 June, Riga, Latvia: https://eahil2024.rsu.lv

Authors: **Floriane Muller** & **Pablo Iriarte**, University of Geneva Library, Switzerland

## Abstract

### Introduction
Tracking and preserving, not to mention opening when possible, an institution’s scholarly output - be it publications or data -, is one of the many missions of libraries. They have been doing so for years, with institutional publication repositories. More recently, data repositories are emerging, boosted by data sharing requirements implemented by journals, institutions and funders. They come in different forms and colours (disciplinary, generic, institutional,…) and aim to replace journal supplementary files services. 
Locating publications and datasets scattered in various places, and linking them together is not an easy task, even in the open science world we live in. Can any repository be really comprehensive and display an accurate picture of an institution’s scientific heritage? Can it contain or link to all datasets accompanying or underlying the publications? 


### Aim
With our research, we intend to: 
 1. Observe data sharing trends in publications by authors affiliated with our institution: are they sharing data more than in the past? are they sharing in supplementary files or in research data repositories? which data repositories? Are those trends comparable with data from other institutions or publishers? is there any noticeable variation between clinical, basic or dental medicine disciplines? 
 2. Identify publications that are missing in our repository, and seek common patterns amongst them: is there any reason or logical explanation for their absence? Are they not deposited in the repository because they cannot be made Open Access? Or on the opposite, because, being OA, authors do not feel the need to deposit them?


### Method
Our institutional repository (launched 15 years ago), our 5 years-old data repository, PubMed, OpenAlex and Datacite Commons will be used to answer our research questions.
Metadata of institutional publications from 2015 to 2022  will be retrieved and analysed using Jupyter Notebooks. As our publication repository is populated by authors and submitted documents undergo verification and metadata enrichment by librarians, supplementary files and links to shared associated data are present in the metadata. For the time being and the relevant timeframe, there are 18’176 records in our publication repository for medicine & life science authors. Of those, 2293 (13%) contains links to shared data, data supplements or appendixes. 
To verify their completeness and accuracy, we will compare them with PubMed (18’502 records for our institution, 7'844 with associated data - 42%), Datacite Commons (987 works), our data repository (794 datasets), OpenAlex (42'380 results) and investigate discrepancies. We also aim to compare our final results with published investigations about other institutions[1] or publishers[2].

### Results:
TBA 

### Conclusion
The results should allow us to inform future decisions, for instance about potential awareness-raising actions and strategic IR changes or inter-connections with other systems.


## Content of repository

 * Notebooks
   * 1_EAHIL_2024_aou_data_extraction
   * 2_EAHIL_2024_aou_data_consolidation.ipynb
   * 3_EAHIL_2024_data_merge_pubmed.ipynb
   * 4_EAHIL_2024_data_merge_openalex.ipynb
   * 5_EAHIL_2024_consolidation_of_data_merged.ipynb
   * 6_EAHIL_2024_results.ipynb
   
 * Folders
   * data: data sources et temporary data
   * figures: graphs generated
   * results: final data with the calculations and aggregations produced

-----------------------------
[1] Barborini, Y., Kuntziger, B., & Chan, P. (2023, September 26). A new way for researchers to deposit files in HAL, the French Open Archive. Presented at the OS Fair 2023, Madrid. Zenodo. doi: 10.5281/ZENODO.8402880

[2] Public Library of Science. (2022). PLOS Open Science Indicators [Data set]. Public Library of Science. doi: 10.6084/m9.figshare.21687686.v4

