# Targeted-MNase-seq-analysis
Analysis pipeline for targeted MNase-seq.

This pipeline aims to analyze nucleosome positioning at individual loci from mapped paired-end MNase-seq data. The input files are locus-specific BAM files.
The code currently takes _FLC_-specific BAMs (which can be obtained from data deposited on GEO) and generates a plot for the entire _FLC_ locus. Although this is currently written to analyze _FLC_-specific BAMs, it can be easily adjusted to any genomic region of interest by modifying the genome coordinates and input BAM files.
For additional information see the paper (_currently unpublished_).
