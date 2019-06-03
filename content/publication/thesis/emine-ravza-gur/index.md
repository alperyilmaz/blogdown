---
abstract: |
  Cellular metabolism embraces elaborate processes which are crucial for the survival of any organism. Understanding the human metabolic system is an important step in enlightening mechanisms of diseases and treatments. After completion of Human Genome Project, human disease studies with holistic approach became prominent which allows analysis of metabolism as a network. Laying out whole metabolic reactions as network and revealing important nodes in metabolic networks has potential to facilitate discovering drug targets and enlightening mechanism of diseases. Genes located in topologically significant points in an interaction or regulatory network have been found to be valuable drug targets. Numerous methods have been proposed to identify significant nodes in networks utilizing standard graph theory measurements such as Degree Centrality, Betweenness Centrality and Closeness Centrality. These measurements provide superficial information about topology of the complex networks and thus are not feasible to detect significant nodes. Although there are various approaches which provide thorough knowledge to measure the significance of nodes by combining fundamental network topology parameters such as clustering coefficient and node neighbourhoods, they fail to accurately identify important nodes. 
  In our thesis, we applied L-value, a recently developed node importance measure, to human metabolic network to identify critical compounds and associated genes. L-value approach considers the total number of triangles in network, degree of nodes and their neighbours. In order to demonstrate that the genes associated with important compounds can be discovered through network analysis only, we gathered differentially expressed genes (DEG) list for several cancer types and then performed gene set enrichment via DAVID web service.  The basis of our approach was that single gene in DEG list that is involved in very crucial reaction will not be identified as “enriched” if there are more than few genes are found in same pathway with this candidate gene. Thus, metabolic network topology should be strongly integrated with DEG analysis in order to uncover genes from a given DEG list which affect critical points in metabolic network. We identified genes that are not in DAVID enrichment sets but associated with critical compounds that have high L-value in metabolic network. In line with the results, genes that do not show enriched in DEGs lists may actually be important, and approach that does not only takes network topology into account but also considers the biochemical effect in DEGs analysis can designate genes that are overlooked in functional enrichment analysis. Our findings has potential to provide novel and insightful aspect on gene expression profile analysis. Our approach was able to recover important genes previously undetected by standard enrichment based approaches. As a result, the veil called "enriched gene" is lifted so that not enriched but critically important genes are exposed. 
authors:
- Emine Ravza Gur
date: "2018-07-01T00:00:00+03:00"
doi: ""
featured: true
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
links:
- name: Custom Link
  url: http://example.org
projects:
- internal-project
publication: In *YILDIZ TEKNİK ÜNİVERSİTESİ*
publication_short: In *YTÜ Fen Bilimleri Enstitüsü*
publication_types:
- "7"
slides: example
summary: .
tags:
- Bioengineering
title: Analysıs Of Bıochemıcal Pathway Wıth Graph Based Algorıthms
url_code: '#'
url_dataset: '#'
url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
url_poster: '#'
url_project: ""
url_slides: ""
url_source: '#'
url_video: '#'
---

{{% alert note %}}
Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
{{% /alert %}}
