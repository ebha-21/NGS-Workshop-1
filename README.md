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

<img width="938" height="496" alt="image" src="https://github.com/user-attachments/assets/a273cac5-db4d-4992-b209-0d9b73cf0308" />

TRIM GALORE is a wrapper script to automate quality and adapter trimming as well as quality control, with some added functionality to remove biased methylation positions for RRBS sequence files.

<img width="661" height="575" alt="image" src="https://github.com/user-attachments/assets/d12c5ddd-75a7-4e16-934e-6bbb58ce7fe4" />


BOWTIE 2 is an ultrafast and memory-efficient tool for aligning sequencing reads to long reference sequences.

<img width="536" height="260" alt="image" src="https://github.com/user-attachments/assets/137b5568-acee-4017-a905-901e10347021" />

<img width="973" height="343" alt="image" src="https://github.com/user-attachments/assets/2561b6a5-e09c-44c8-bd2d-7ff834ae25fd" />

<img width="688" height="572" alt="image" src="https://github.com/user-attachments/assets/fb734100-6741-47a5-8cf5-4e847d9162f6" />

FEATURECOUNT: FeatureCounts is a light-weight read counting program written entirely in the C programming language. It can be used to count both gDNA-seq and RNA-seq reads for genomic features in in SAM/BAM files. FeatureCounts is part of the Subread package.

<img width="960" height="580" alt="image" src="https://github.com/user-attachments/assets/11caced7-0c1f-4e95-bdbd-36a970a0091d" />

DESeq2 : DESeq2 is a bioinformatics software package used to analyze RNA-sequencing (RNA-seq) data, especially to find differentially expressed genes.
In simple words DESeq2 helps you answer:Which genes are more or less active between two (or more) biological conditions?
For example:healthy vs diseased cells
            treated vs untreated samples
            control vs experiment
            
<img width="987" height="590" alt="image" src="https://github.com/user-attachments/assets/b420c85a-8325-44dc-9704-f2d385e58c66" />

<img width="959" height="570" alt="image" src="https://github.com/user-attachments/assets/6afee207-f53e-4f83-802c-95ea91e57d22" />





