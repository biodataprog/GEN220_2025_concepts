# GEN220: Computational Analysis of High Throughput Biological Data

Focus: Bioinformatics and Data Plumbing
Revamped Concept Teaching for GEN220

## Data focused with UNIX, Python, and R

1. Column data focused extraction and analysis (CSV, TSV, BED, GFF)
  * csv processing with csvkit and cut
  * cut, sort, uniq, wc to counting lines that match, getting aggregate numbers
3. Coordinate analysis, overlap
   * BEDtools
   * SNPs overlapping genes, what are the genes with most SNPs?
   * How many bases / % of genome are repeats? How many for each class of repeats?
4. Comparative content
   * Orthology, Gene family presence/absence/copy number patterns
   * Venn/Upset plots

## Data munging

1. Converting file formats
   * Sequence data examples
3. Writing simple python processing
   * Bulk renaming or reformatting data

## Genomics and Evolutionary focused data

1. Sequence data types
2. Genome assembly
    * Long read assembly tools (w/ polishing or hybrid assembly)
    * Short read assembly tools
3. Genome annotation
   * Bacteria focused (prodigal and prokka and beav)
4. Read and sequence alignment
    * BLAST and FASTA
    * minimap2
    * bwa, bwa-mem2
    * LAST
5. Population data
    * Variant calling into VCF format
    * VCF querying, reprocessing with bcftools
    * vcfR to visualize and QC
    * PCA and Trees from VCF
    * Structure plots
6. Viz genome datasets
7. Phylogenetic tree construction and aggregation
    * Plotting trees in ggtree
    * Summarizing trees
8. RNAseq
    * kallisto to get TPM
9. Synteny visualization and analysis
