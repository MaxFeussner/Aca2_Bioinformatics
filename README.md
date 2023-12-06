# Aca2_Bioinformatics

### Aca2_hmm
Output of OperonExtract: Contains all Aca2 operons extracted from the IMGVR database and their links to the IMGVR contigs.

### Aca2_promoters_0.99.fa
Fasta file containing the Aca2 operons after removal of the redundant ones with cd-hit (threshold: 0.99% sequence identity).

### Actino_host_seed_alignment.sto
Seed alignment used for the actinomotif confidence set in Stockholm format.

### Actino_host_confidence_set_0.001_1.align
Confidence set built from seed alignment after two iterations of cmsearch with an E-value threshold of 0.001.

### Proteo_host_seed_alignment.sto
Seed alignment used to build the confidence set for the proteomotif in Stockholm format.

### Proteo_host_confidence_set_0.001_1.align
Confidence set built from seed alignment after two iterations of cmsearch with an E-value threshold of 0.001.

### meta_info_virus.tsv
Metadata from the IMGVR database for all Aca2 operons used for host assignment.

### IR1_IR2_AA_helix3.stk
Stockholm file containing the nucleotide sequence of IR1 and IR2 and the amino acid sequence of helix3 of Aca2 for analysing the covariation between Aca2 and the DNA and RNA motifs.

### IR1_IR2_AA_helix3_indicated_covary.stk
Same sequences as IR1_IR2_AA_helix3.stk but with additional nucleotide and amino acid predicted to covary.

### IR2_AA_helix3.fa
Stockholm file containing the nucleotide sequence of IR2 and the amino acid sequence of helix3 of Aca2 to analyse the covariation between Aca2 and the RNA motifs.
