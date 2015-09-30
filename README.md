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

# Schedule

## Monday

Morning

- Introduction to _R_ and _Bioconductor_

Afternoon

- Working with sequence data in _Bioconductor_
    - Overall sequence work flows
    - Key _Bioconductor_ packages and classes
    - 'Annotation' resources
    - Working with large data
    - Common bioinformatics tasks, easy _Bioconductor_ solutions

- Participant lightning talks -- short, _ad hoc_ or lightly prepared
  presentations by workshop participants to introduce their work. A
  couple of participants will volunteer during each time slot
  throughout the course.

## Tuesday

Morning

- Variant annotation and calling
    - Working with called variants: VCF files, [VariantAnnotation][],
      [VariantFiltering][].
    - Calling variants. Common workflows outside
      _Bioconductor_. Alternative approaches in _Bioconductor_.

- Participant lightning talks -- short, _ad hoc_ or lightly prepared
  presentations by workshop participants to introduce their work. 

Afternoon

- RNA-seq differential expression. 
    - Overall work flow, statistical issues, and implementation using
      [DESeq2][] and [edgeR][]
    - [kallisto][] and other newer approaches; [limma][] `voom()`.

- Participant lightning talks -- short, _ad hoc_ or lightly prepared
  presentations by workshop participants to introduce their work. 

## Wednesday

Morning

- One of:
    - Working with large data 
    - [csaw][], [ChIPseeker][] and other ChIP-seq analysis
    - gene set and other down-stream analysis facilities.

- Participant lightning talks -- short, _ad hoc_ or lightly prepared
  presentations by workshop participants to introduce their work. 

Afternoon

- Data visualization and reporting
    - Static visualization, e.g., [Gviz][]
    - [shiny][] for interactive visualizations
    - [ReportingTools][] for effective and flexible reports
    - Sharing interactive results to your less-fortunate
      _R_-illiterate colleagues

[VariantAnnotation]: https://bioconductor.org/packages/VariantAnnotation
[VariantFiltering]: https://bioconductor.org/packages/VariantFiltering
[DESeq2]: https://bioconductor.org/packages/DESeq2
[edgeR]: https://bioconductor.org/packages/edgeR
[limma]: https://bioconductor.org/packages/limma
[csaw]: https://bioconductor.org/packages/csaw
[ChIPseeker]: https://bioconductor.org/packages/ChIPseeker
[Gviz]: https://bioconductor.org/packages/Gviz
[ReportingTools]: https://bioconductor.org/packages/ReportingTools

[shiny]: http://shiny.rstudio.com/
[kallisto]: http://pachterlab.github.io/kallisto

