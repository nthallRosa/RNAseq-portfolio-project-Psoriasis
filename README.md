# RNAseq portfolio project: Psoriasis and associated comorbidities
## **Bulk RNA-seq re-analysis of lesional psoriasis skin reveals shared molecular links with psoriatic arthritis and cardiovascular comorbidities**
### Project overview
This project was developed as a skills demonstration to highlight my ability to use R for bulk RNA-seq analysis, apply common bioinformatics workflows, and think critically about biological results. It is not intended to present novel research findings, but rather to showcase my proficiency with data handling, differential expression analysis, visualization, and interpretation within a real biological context.
### Biological context and project goals
Psoriasis is a debilitating autoimmune disease characterized by inflammation and hyperproliferation of skin cells. Many psoriasis patients also experience several comorbidities. These would include illnesses such as cardiovascular disease, psoriatic arthritis, inflammatory bowel disease, and many more. While much progress has been made when it comes to diagnosing and treating the skin disease, mechanisms connecting psoriasis to these comorbidities are incompletely understood, and some such as psoriatic arthritis contain no diagnostic test. The goal of this project is to identify gene expression patterns that best characterize psoriasis and serve as predictors for development of future comorbidities.
### Tools
- Rstudio ()
- R()
- DESeq2
- EnhancedVolcano()
- dplyr()
- clusterProfiler()
- org.Hs.eg.db()
- enrichplot()
- pathview()
- VennDiagram()
- stringr()

<img width="715" height="606" alt="Screen Shot 2025-12-07 at 1 56 36 PM" src="https://github.com/user-attachments/assets/9a07e678-de96-49be-98dd-d86aef3d8a2b" />




### Key Findings
- Classic psoriasis signature confirmed: strong upregulation of IL36A, CXCL8, DEFB4B, S100A family, and SPRR genes driving keratinocyte hyperproliferation, antimicrobial defense, and immune-cell recruitment.
- Rheumatoid arthritis KEGG pathway (hsa05323) unexpectedly enriched in lesional psoriasis skin (ES = 0.73), with five pathway genes directly feeding into the IL-17 signaling axis central to psoriasis pathogenesis.
- Multiple psoriatic arthritis-associated genes (CXCL9, CXCL10, CSF1, DCST2) significantly elevated, suggesting potential as an early screening panel for PsA development in psoriasis patients.
- Cardiovascular-related pathways (calcium signaling hsa04020, ES = -0.41; cardiac muscle contraction hsa04260, ES = -0.55) also enriched, hinting at shared transcriptional mechanisms with cardiometabolic comorbidities.
