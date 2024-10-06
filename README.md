# Phylogenomic-pipeline-for-microbial-eukaryotes

A Phylogenomic workflow for uncultivable microbial eukaryotes using single-cell RNA sequencing - single cell isolation to species tree construction

(A) Phylogenomic pipeline

1. RAW sequence data processing
QC checking
Trimming
Assembling


2. Post assembly pipeline and single gene tree construction
(I) Post assembly pipeline
(II) Summarize nucleotide composition statistics for a fasta file
(III) Multiple sequence alignments (MSA)
(IV) Single gene tree construction


3. Data curation
(I) Select clades of interest from large trees using taxonomic specifications
(II) Remove low coverage sequences
(III) Only keeping ortholog sequences


4. Concatenation-based phylogenomic approach
(I) Multiple sequence alignments (MSA) (only for dataset includes single-copy genes)
(II) Trimming MSA
(III) Concatenation of MSA
(IV) Maximum likelihood Tree
(V) Likelihood mapping


5. Species tree using Asteroid
(I) Single gene tree construction (dataset includes multi-copy genes)
(II) Species tree construction


(B) rRNA genes reconstruction

(I) Read mapping
(II) Contig assembling

(C) rRNA phylogeny

(I) Multiple sequence alignments (MSA)
(II) Trimming MSA
(III) Maximum likelihood Tree
