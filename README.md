# DataFiles
This is a repository for storing datasets described in https://www.biorxiv.org/content/10.1101/564823v1

DATA S1 includes SSU rRNA gene sequencing OTU table with OTU counts, relative abundances, reference sequences and estimated taxonomy.				
SSU rRNA gene sequencing targeting the V6–V8 variable region of the 16S rRNA gene from bacteria and archaea as well as the 18S rRNA gene in eukarya was performed on Illumina MiSeq System (PE300).The analysis of sequencing reads was performed with QIIME1 package by joining forward and reverse reads (multiple_join_paired_ends.py, min overlap 50 bp, max mismatch allowance 8), removing low-quality sequences (multiple_split_libraries_fastq.py, quality threshold 19), removing chimeric sequences and identifying operational taxonomic units at 97% similarity (identify_chimeric_seqs.py, pick_open_reference_otus.py, method usearch61, reference database SILVA release 128). 						

DATA S2 includes the relative abundance of ARGs per 16S rRNA gene detected from total community metagenome sequencing reads with ARGs-OAP using default settings.								
