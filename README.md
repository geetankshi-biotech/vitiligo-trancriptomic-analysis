# vitiligo-trancriptomic-analysis
Patient-aware transcriptomic exploration of immune, TRM-associated and metabolic programmes across vitiligo skin regions using the GSE311770 dataset.
# Vitiligo Transcriptomic Analysis

### Exploring immune, tissue-residency-associated and metabolic gene-expression programmes in vitiligo skin

## About the Project

Vitiligo is an autoimmune skin disorder characterised by the destruction of melanocytes, the pigment-producing cells of the skin.

Tissue-resident memory T cells (TRM cells), particularly CD8+ T cells, are implicated in maintaining local immune responses and may contribute to disease recurrence.

This project aims to investigate regional gene-expression patterns associated with immune activity, TRM-associated programmes and cellular metabolism in vitiligo skin using publicly available RNA-sequencing data.

The analysis focuses on understanding how these molecular programmes vary across different skin regions and whether they show relationships with one another.

## Research Question

How do TRM-associated transcriptional signatures relate to immune-effector and metabolic programmes across lesional, perilesional and non-lesional vitiligo skin?

This is a provisional research question under literature and feasibility assessment.

## Dataset

**GEO Accession:** GSE311770

**Study:** Berrevoet et al. (2026)

**Dataset type:** Bulk RNA sequencing

**Total samples:** 105

| Tissue group | Number of samples |
|---|---:|
| Lesional skin | 24 |
| Perilesional skin | 27 |
| Non-lesional skin | 27 |
| Healthy control skin | 27 |

The dataset contains gene-expression count data and corresponding sample metadata.

Dataset source: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE311770

## Research Objectives

1. Characterise gene-expression patterns across different vitiligo skin regions.
2. Investigate TRM-associated transcriptional signatures.
3. Explore immune-effector and inflammatory gene-expression programmes.
4. Examine metabolic pathways, including:
   - Fatty-acid metabolism
   - Oxidative phosphorylation
   - Glycolysis
5. Explore relationships between immune-associated and metabolic signatures.
6. Interpret findings in the context of existing vitiligo research.

## Computational Workflow

The planned workflow includes:

1. Dataset acquisition and metadata processing.
2. Expression matrix inspection and quality control.
3. Gene filtering and appropriate normalization.
4. Exploratory analysis and PCA.
5. Patient-aware differential gene-expression analysis.
6. Gene-signature scoring.
7. Functional and pathway enrichment analysis.
8. Integrated biological interpretation.
9. Independent validation, if a suitable dataset is available.

## Tools and Technologies

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- R
- edgeR
- Gene Expression Omnibus (GEO)

## Current Progress

### Completed
- Downloaded the GSE311770 gene-expression count matrix.
- Retrieved and processed GEO sample metadata.
- Matched all 105 expression samples with sample metadata.
- Examined tissue-group distribution.
- Performed initial expression-count and library-size quality checks.
- Reviewed the original dataset publication and related literature.

### In Progress
- Literature and novelty assessment.
- Verification of count-data provenance.
- Finalisation of the statistical analysis design.
- Public supplementary-data feasibility assessment.

### Planned
- Normalisation and exploratory analysis.
- Differential gene-expression analysis.
- TRM-associated and immune-effector signature analysis.
- Metabolic pathway analysis.
- Integrated interpretation of regional expression patterns.

## Important Methodological Considerations

This study uses bulk RNA sequencing. Therefore, gene-expression signatures cannot independently establish the identity, abundance or functional activity of individual cell populations.

TRM-associated transcriptional signatures will be interpreted cautiously and will not be treated as direct evidence of TRM cell persistence.

Repeated biopsies from the same patient will be accounted for in the statistical design.

The project is exploratory, and biological conclusions will be based on the results of the completed analysis rather than assumed in advance.

## References

1. Berrevoet et al. (2026). Minimally invasive 1 mm skin biopsies capture site-specific transcriptomic heterogeneity in vitiligo. Frontiers in Immunology.
2. Shiu et al. (2022). Multimodal analyses of vitiligo skin identify tissue characteristics of stable disease. JCI Insight.
3. Pan et al. (2017). Survival of tissue-resident memory T cells requires exogenous lipid uptake and metabolism. Nature.

## Project Status

Early-stage computational research project. Dataset acquisition, metadata processing and initial quality assessment have been completed. Downstream biological analysis is planned.
