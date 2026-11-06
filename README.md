## 1468

### Analysis Completed to Date (November 2026)

1. Processed mouse colonic endothelial scRNA-seq data from 8 libraries representing 24 expected mice across the DSS colitis time course. Endothelial cells were enriched by flow cytometry prior to sequencing.
2. Performed RNA quality control to evaluate cell quality and filtering.
3. Performed hashtag (HTO) demultiplexing to identify individual mice and distinguish singlets, doublets, and negative droplets.
4. Evaluated sample composition and HTO assignment quality across all 8 libraries.
5. Annotated cells using SingleR and Mouse Cell Atlas (MCA) reference datasets.
6. Evaluated endothelial identity in the flow-enriched samples and performed additional clustering, resulting in 16 endothelial-enriched clusters.
7. Examined canonical endothelial marker expression to characterize potential capillary, arterial, venous, and lymphatic endothelial populations.
8. Compared endothelial clusters with colon endothelial subtype signatures from Kalucka et al. (2020), including sensitivity analyses using the top 20, 50, and 100 ranked marker genes.
9. Evaluated agreement and ambiguity among candidate endothelial subtype assignments to support PI-guided annotation.
10. Examined library and DSS time-point distributions across endothelial clusters.
11. Generated an interactive HTML report summarizing QC, HTO demultiplexing, endothelial selection, reclustering, reference-based annotations, canonical markers, and Kalucka colon endothelial signatures.

### Endothelial Annotation Status

Endothelial subtype annotations are currently provisional and will be finalized following PI review.

Candidate identities are supported by multiple sources of evidence, including canonical endothelial markers, SingleR/MCA reference annotations, and Kalucka colon endothelial signatures.

Some clusters have relatively clear subtype signatures, while others show overlapping or cutoff-dependent assignments that require biological interpretation. Broader endothelial labels may be retained when subtype-specific evidence is insufficient.

The analysis report is intended to provide supporting evidence for PI annotation decisions rather than automatically assign final endothelial identities.

### Next Steps

1. Confirm DSS day assignments and sample metadata.
2. Review candidate endothelial subtype identities with the PI and finalize the cluster-to-subtype annotation mapping.
3. Update the Seurat object with the agreed endothelial annotations.
4. Compare endothelial cell proportions across DSS time points to identify changes during inflammation and recovery.
5. Perform differential gene expression analysis to identify DSS-associated transcriptional changes within endothelial populations, accounting for biological replication and study design.
6. Conduct pathway enrichment analysis to investigate biological processes associated with DSS-induced colitis.
7. Integrate cell proportion, differential expression, and pathway results to identify key endothelial responses during inflammation and recovery.

### Current HTML Report

**Step 1: QC, HTO Demultiplexing, and Endothelial Annotation**

[View HTML Report on GitHub](https://github.com/foocheung/1468-colitis/blob/main/Reports/NIAID1468_01_QC_annotation_PI_first_pass_v4.html)

To view the report correctly, download the HTML file from GitHub and open it locally in a web browser (Chrome, Firefox, or Safari). GitHub does not render the interactive HTML report directly.

**Status:** Initial QC, HTO demultiplexing, endothelial reclustering, and candidate subtype characterization completed. Final endothelial subtype annotations are pending PI review. Downstream DSS time-course analyses are planned.
