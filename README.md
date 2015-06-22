This course provides a broad introduction to the analysis and
comprehension of high-throughput sequence data using R and
Bioconductor; many other useful software tools are not discussed.  The
topics and learning objectives to be address are as follows:

- Introduction to Bioconductor: Familiarity with overall sequence
  analysis work flows. The diversity of analysis challenges addressed
  by Bioconductor. The role of Bioconductor packages in specific work
  flow steps. Bioconductor resources for help and effective use.

- Next Generation Sequencing data manipulation: Common genomic file
  types (FASTA/FASTQ, BED, WIG, GTF, etc) and their Bioconductor
  representation and manipulation. Essential Bioconductor data
  structures (e.g., DNAStringSet, GenomicRanges). Bioconductor gene
  and genome 'annotation' resources. Simple Bioconductor solutions to
  common bioinformatic tasks. Primary packages: GenomicFiles,
  GenomicRanges, GenomicFeatures, ShortRead, Biostrings.

- Variant calling and annotation: Conceptual understanding of variant
  calling approaches and (primarily non-Bioconductor)
  tools. Exploratory approaches to variant calling in
  Bioconductor. Working with called variants, e.g., classifying
  variants to genomic regions of interest and predicting effects of
  variants. Primary packages: VariantTools, r5vc, VariantAnnotation.

- RNA-seq differential expression analysis: Bioconductor known-gene
  RNA-seq differential expression work flow, from aligned reads to
  differential expression of genes. Important statistical issues and
  their resolution. Placing results of differential expression
  analysis into biological context. Brief discussion of novel-gene and
  transcript-level RNAseq differential expression analysis. Primary
  packages: DESEq2, edgeR.

- Working with large data: Overcoming common pitfalls in memory
  management and computational throughput when writing R
  code. Adopting restriction, iteration, and parallel evaluation
  strategies for working with large data. Primary packages:
  BiocParallel, GenomicFiles.

- Data visualization: Challenges to visualizing genomic
  data. Opportunities for familiar and novel genomic visualizations in
  Bioconductor. Approaches to interactive visualization with
  shiny. Adopting strategies for reproducible and collaborative
  research. Primary packages: Gviz, ReportingTools, (ggbio).

Additional topics may be discussed briefly and on an ad hoc basis. 

<!-- 
Following up on the January meeting and in preparing the course, I
would like to confirm with you the topics we selected for this course
and ask you some details about learning objectives that we will
communicate to participants.

Could you thus:

- Confirm that the selected topics are ok;
- Provide some short sentences describing learning objectives for each of these topics
- Indicate softwares and versions that will be needed on laptops/cloud
 -->
