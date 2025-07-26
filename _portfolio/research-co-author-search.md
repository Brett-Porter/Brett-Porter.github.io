---
title: "Research Co-author Search"
excerpt: "A Python script that searches PubMed for co-authored articles and fetches citations using the E-Utilities API."
header:
  teaser: /assets/images/portfolio/pubmed-search-teaser.png # Optional: Change to a screenshot of your project.
portfolio: true
tags:
  - Python
  - API
  - Biomedical Informatics
---

This project is a Python script designed to assist researchers in finding co-authored articles. It leverages the Entrez Programming Utilities (E-Utilities) API provided by the National Library of Medicine to search PubMed for articles by specific authors and fetch their citations.

The script is a valuable tool for building bibliographies, analyzing co-authorship networks, and keeping track of research team publications. It was developed primarily as a utility for the National Network of Libraries of Medicine (NNLM) to support research teams.

### Features
* **PubMed Search:** Queries the PubMed database for articles.
* **Co-authorship Filtering:** Identifies and fetches articles where multiple specified authors are listed.
* **Citation Retrieval:** Gathers detailed citation information for each found article.
* **API Integration:** Demonstrates practical use of the E-Utilities API.

### Technical Details
* **Language:** Python
* **Libraries:** `requests`, `xml.etree.ElementTree` (or similar for XML parsing)
* **API:** Entrez Programming Utilities (E-Utilities)
* **Repository:** [https://github.com/NNLM-NCDS/research-team-co-authorship](https://github.com/NNLM-NCDS/research-team-co-authorship)

<p><em>(Primary coder)</em></p>
