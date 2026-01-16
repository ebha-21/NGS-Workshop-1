# NGS-Workshop-1
INTRODUCTION - NEXT GENERATION SEQUENCING - Next-Generation Sequencing (NGS), also called high-throughput sequencing, is a set of technologies that determine the order of nucleotides (A, T, C, G) in DNA or RNA at massive scale.
Uses massively parallel sequencing—thousands to millions of DNA molecules are sequenced at once.
Much faster and cheaper compared to traditional Sanger sequencing. Basics of DNA Sequencing - DNA sequencing is a laboratory technique used to identify the precise sequence of nucleotides (adenine, thymine, cytosine, guanine) in DNA .
Provides a genetic blueprint of organisms , allowing researchers to study genes, mutations, and regulatory regions.
Essential for genomics, medical diagnostics, biotechnology, and evolutionary biology.
In this workshop we covered CENTRAL DOGMA -
CENTRAL DOGMA - The central dogma explains how genetic information flows inside a cell.
Pathway: DNA to RNA to Protein
We also practised some hands-on activities -
All the work was done using Galaxy an open source, web-based platform for data intensive biomedical research. For data download we used https://zenodo.org/records/4249555 We used Raw mouse mammary RNA-Seq data (fastq) , uploaded the 4 files on galaxy and used certain tools - Screenshot 2026-01-15 163856

FASTQC on dataset and webpage - FastQC aims to provide a simple way to do some quality control checks on raw sequence data coming from high throughput sequencing pipelines. Screenshot 2026-01-15 165253
TRIM GALORE is a wrapper script to automate quality and adapter trimming as well as quality control, with some added functionality to remove biased methylation positions for RRBS sequence files.
Screenshot 2026-01-15 170144
BOWTIE 2 is an ultrafast and memory-efficient tool for aligning sequencing reads to long reference sequences.
Screenshot 2026-01-15 170936
