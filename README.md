# Kv82_biomarkers
Analysis files for Laird et al 2026
# Kv8.2 retinal biomarker analyses

Analysis code and OCT measurement data accompanying Laird et al. (2026).

## OCT_statistics

Contains the Quarto (.qmd) file used to generate the OCT statistical
outputs in Supplemental File S1, including linear mixed models,
estimated marginal means, and genotype and lighting-condition contrasts.

The input workbook, Kv82_exp7_all_biomarkers.xlsx, contains the
ELM-RPE and ONL measurements. Keep the workbook in the same folder
as the .qmd file when running the analysis.

## RNAseq

Contains the Quarto (.qmd) source for the RNA-seq analysis presented
in Supplemental File S2.

RNA-seq data are deposited in the Gene Expression Omnibus under
accession GSE327286:
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE327286

The manuscript Methods and Supplemental File S2 describe the
processing workflow, analysis parameters, and software versions.
Local file paths in the .qmd must be updated before running the analysis.

## Software

The analyses use R and Quarto. Required R packages are identified
in the .qmd files. Rendering PDF output also requires a LaTeX installation.
