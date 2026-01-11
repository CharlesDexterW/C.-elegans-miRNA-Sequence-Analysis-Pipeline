# C.-elegans-miRNA-Sequence-Analysis-Pipeline
This is an automated Bash pipeline for reproducible miRNA analysis from miRBase v22. I used C. elegans (lin-4/let-7) precursors using SeqKit for biochemical metric extraction.

## Biological Context
MicroRNAs are small non-coding RNA molecules (~22nt) that play a critical role in post-transcriptional gene regulation. This pipeline focuses on:

**cel-lin-4:** The first miRNA discovered, essential for larval development.

**cel-let-7:** A highly conserved regulator of developmental timing.

The script automates the extraction of these precursors, converts the RNA sequences to DNA for downstream compatibility, and calculates key biochemical metrics such as GC Content.

## Features
**Reproducibility:** Targets a static version of the miRBase database (v22).

**Automation:** One-touch execution from download to final report.

**Efficiency:** Optimized for multi-core processing (Intel i5-1235U) using SeqKit.

**Data Transformation:** Converts raw FASTA data into structured TSV tables.

## Installation & Usage
### Prerequisites
Ensure you have seqkit installed on your Ubuntu system:
