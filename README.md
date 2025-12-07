<div id="toc">
  <ul style="list-style: none">
    <summary>
      <h1 align="center"> RNAseq portfolio project: Psoriasis and associated comorbidities </h1>
    </summary>
  </ul>
</div>
<h2 align="center"> Bulk RNA-seq re-analysis of lesional psoriasis skin reveals shared molecular links with psoriatic arthritis and cardiovascular comorbidities </h2>

### Project overview
This project was developed as a skills demonstration to highlight my ability to use R for bulk RNA-seq analysis, apply common bioinformatics workflows, and think critically about biological results. It is not intended to present novel research findings, but rather to showcase my proficiency with data handling, differential expression analysis, visualization, and interpretation within a real biological context.
### Biological context and project goals
Psoriasis is a debilitating autoimmune disease characterized by inflammation and hyperproliferation of skin cells. Many psoriasis patients also experience several comorbidities. These would include illnesses such as cardiovascular disease, psoriatic arthritis, inflammatory bowel disease, and many more. While much progress has been made when it comes to diagnosing and treating the skin disease, mechanisms connecting psoriasis to these comorbidities are incompletely understood, and some such as psoriatic arthritis contain no diagnostic test. The goal of this project is to identify gene expression patterns that best characterize psoriasis and serve as predictors for development of future comorbidities.

<p>
  <img src="https://github.com/user-attachments/assets/9a07e678-de96-49be-98dd-d86aef3d8a2b" width="32%" />
  <img src="https://github.com/user-attachments/assets/2e5adfd5-a7dc-4fd5-a318-dc35691617b6" width="32%" />
  <img src="https://github.com/user-attachments/assets/8f830f71-0298-4dcc-8121-0e6cff1e19a1" width="32%" />
</p>


### Key Findings
- Classic psoriasis signature confirmed: strong upregulation of IL36A, CXCL8, DEFB4B, S100A family, and SPRR genes driving keratinocyte hyperproliferation, antimicrobial defense, and immune-cell recruitment.
- Rheumatoid arthritis KEGG pathway (hsa05323) unexpectedly enriched in lesional psoriasis skin (ES = 0.73), with five pathway genes directly feeding into the IL-17 signaling axis central to psoriasis pathogenesis.
- Multiple psoriatic arthritis-associated genes (CXCL9, CXCL10, CSF1, DCST2) significantly elevated, suggesting potential as an early screening panel for PsA development in psoriasis patients.
- Cardiovascular-related pathways (calcium signaling hsa04020, ES = -0.41; cardiac muscle contraction hsa04260, ES = -0.55) also enriched, hinting at shared transcriptional mechanisms with cardiometabolic comorbidities.


### Quick Start (fully reproducible)
```bash
git clone https://github.com/yourusername/RNAseq-portfolio-project-Psoriasis.git
cd RNAseq-portfolio-project-Psoriasis
conda env create -f environment.yml
conda activate psoriasis-rnaseq
R -e "rmarkdown::render('Psoriasis_RNAseq_Analysis.Rmd')"
```
*** Important to note that version of tools such as org.Hs.eg.db could lead to slightly different results ***

### Tools
- Rstudio (2025.5.1.513.3)
- R(4.5.2)
- DESeq2(1.50.2)
- EnhancedVolcano(1.29.1)
- dplyr(1.1.4)
- clusterProfiler(4.18.2)
- org.Hs.eg.db(3.22.0)
- enrichplot(1.30.3)
- pathview(1.50.0)
- VennDiagram(1.7.3)
- stringr(1.6.0)
