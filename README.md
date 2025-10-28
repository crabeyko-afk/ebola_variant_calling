# Ebola Variant Calling Project 

This repository contains my work for the Ebola virus variant calling workflow using the Bioinformatics Toolbox.

##  Overview
I followed the workflow described in the handbook to identify variants in the Ebola virus genome (2014 outbreak) compared to the 1976 reference strain.

##  Steps performed
1. Installed the Bioinformatics Toolbox with `bio code`.
2. Created a Makefile to automate the variant calling pipeline.
3. Downloaded the Ebola reference genome (`GCA_000848505`).
4. Downloaded sequencing reads for sample `SRR1553425` (sample alias `EM110`).
5. Ran the workflow:
   ```bash
   make bam
   make vcf

