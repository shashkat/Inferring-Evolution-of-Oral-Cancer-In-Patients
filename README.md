# Inferring-Evolution-of-Oral-Cancer-In-Patients
My research project at IITK under Professor Hamim Zafar, involving analysis of oral tumor sequencing data, and making inferences about evolution from it.

Currently, have made one trial run on a tumor sample (head and neck type), taking the bam file from icgc database, and running it through mutect2, to get the VCF file with SNV data. Also used a tool called CNVpytor to get CNV data from the same alignment file. These two were given as inputs to DeCiFer tool, to produce the main DeCiFer input file, which when given to it as input, would yield the evolution pattern of the tumor.

Working on using a consesnsus approach to get CNVs (Battenberg and ABSOLUTE), as that will yield a better result.
