# Phylogenomic-pipeline-for-microbial-eukaryotes

A Phylogenomic workflow for uncultivable microbial eukaryotes using single-cell RNA sequencing - single cell isolation to species tree construction

(A) Phylogenomic pipeline
1. RAW sequence data processing
  a. QC checking
  b. Trimming
  c. Assembling

2. Post assembly pipeline and single gene tree construction
   a. Post assembly pipeline
   b. Summarize nucleotide composition statistics for a fasta file
   c. Multiple sequence alignments (MSA)
   d. Single gene tree construction


3. Data curation
   a. Select clades of interest from large trees using taxonomic specifications
   b. Remove low coverage sequences
   c. Only keeping ortholog sequences


4. Concatenation-based phylogenomic approach
   a. Multiple sequence alignments (MSA) (only for dataset includes single-copy genes)
   b. Trimming MSA
   c. Concatenation of MSA
   d. Maximum likelihood Tree
   e. Likelihood mapping


5. Species tree using Asteroid
   a. Single gene tree construction (dataset includes multi-copy genes)
   b. Species tree construction


(B) rRNA genes reconstruction

1. Read mapping
2. Contig assembling

(C) rRNA phylogeny

  a. Multiple sequence alignments (MSA)
  b. Trimming MSA
  c. Maximum likelihood Tree
