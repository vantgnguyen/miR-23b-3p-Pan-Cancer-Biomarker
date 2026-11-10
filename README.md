# Circulating hsa-miR-23b-3p as a Candidate Biomarker for Pan-Cancer Detection Across 13 Cancer Types
This repository contains the poster and analytical figures for evaluating whether circulating *hsa-miR-23b-3p* alone can discriminate cancer patients from healthy controls across 13 cancer types, and exploring its biological relevance through target-gene and network analysis.
The research is performed using published serum miRNA data from GEO (4 cohorts: GSE112264, GSE211692, GSE106817, GSE113486). No clinical experiments are performed.
## Repository Structure

```
miR-23b-3p-Pan-Cancer-Biomarker/
│
├── BME11 - Poster .pdf        # Conference poster presentation document
├── Fig 1.jpeg                 # Study workflow
├── Fig 2.png                  # Expression of hsa-miR-23b-3p in healthy controls and 13 cancer types
├── Fig 3.png                  # ROC curves across four GEO cohorts
├── Fig 4.png                  # Precision-recall curves across four GEO cohorts
├── Fig 5.png                  # GO and KEGG enrichment of predicted target genes
├── Fig 6.png                  # Protein-protein interaction (PPI) network of target genes
├── Supplementary Fig 1.png    # Expression of hub target genes in tumor vs. normal tissues
└── README.md                  # Project documentation
```

## Methods

- **Data:** 4 GEO serum miRNA cohorts (n = 1,350; 14,458; 3,938; 972)
- **Statistics:** Wilcoxon rank-sum test
- **Diagnostic evaluation:** ROC curve (AUC) and precision-recall curve (AP)
- **Target prediction:** miRWalk and miRDB (score ≥ 0.80), yielding 677 predicted target genes
- **Functional analysis:** GO, KEGG and protein-protein interaction network

## Key Findings

- *hsa-miR-23b-3p* was elevated in all 13 cancer types compared with healthy controls (p < 0.0001).
- It best discriminated lung, gastric and pancreatic cancers, consistently across four independent cohorts.
- Predicted target genes were enriched in cancer-related pathways (MAPK, mTOR, FoxO, ErbB).
- *hsa-miR-23b-3p* is a promising candidate for minimally invasive screening, but prospective validation is needed before clinical use.

## Authors
Thi Tuong Van Nguyen
