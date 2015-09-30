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

# Tentative Schedule

## Monday

9:00 - 12:30 (break 10:30 - 11:00)

- Introduction to _R_ and _Bioconductor_
    - From vectors to objects
    - Help! and other resources
    - Why _Bioconductor_? [SummarizedExperiment][]

1:30 - 5:00 (break 3:00 - 3:30)

- Working with sequence data in _Bioconductor_
    - Overall sequence work flows
    - Key _Bioconductor_ packages and classes -- [GenomicRanges][],
      [Biostrings][], [ShortRead][], [rtracklayer][]
    - 'Annotation' resources -- [GenomicFeatures][],
      [AnnotationHub][], [biomaRt][]
    - Working with large data -- [BiocParallel][], [GenomicFiles][]
    - Common bioinformatics tasks, easy _Bioconductor_ solutions

- Participant lightning talks -- short, _ad hoc_ or lightly prepared
  presentations by workshop participants to introduce their work. A
  couple of participants will volunteer during each time slot
  throughout the course.

## Tuesday

9:00 - 12:30 (break 10:30 - 11:00)

- Variant annotation and calling
    - Working with called variants: VCF files, [VariantAnnotation][],
      [VariantFiltering][].
    - Calling variants. Common workflows outside
      _Bioconductor_. Alternative approaches in
      _Bioconductor_. [VariantTools][], [r5vc][].

- Participant lightning talks -- short, _ad hoc_ or lightly prepared
  presentations by workshop participants to introduce their work. 

1:30 - 5:00 (break 3:00 - 3:30)

- RNA-seq differential expression. 
    - Overall work flow, statistical issues, and implementation using
      [DESeq2][] and [edgeR][]
    - [kallisto][] and other newer approaches; [limma][] `voom()`

- Participant lightning talks -- short, _ad hoc_ or lightly prepared
  presentations by workshop participants to introduce their work. 

## Wednesday

9:00 - 12:30 (break 10:30 - 11:00)

- One of:
    - Working with large data [GenomicFiles][], [BiocParallel][]
    - [csaw][], [ChIPseeker][] and other ChIP-seq analysis
    - Gene set and other down-stream analysis facilities. [limma][]
      gene set functions, [Category][], [GOstats][], [WGCNA][].

- Participant lightning talks -- short, _ad hoc_ or lightly prepared
  presentations by workshop participants to introduce their work. 

1:30 - 5:00 (break 3:00 - 3:30)

- Data visualization and reporting
    - Static visualization, e.g., [Gviz][]
    - [shiny][] for interactive visualizations
    - [ReportingTools][] for effective and flexible reports
    - Sharing interactive results to your less-fortunate
      _R_-illiterate colleagues

[AnnotationHub]: https://bioconductor.org/packages/AnnotationHub
[BiocParallel]: https://bioconductor.org/packages/BiocParallel
[Biostrings]: https://bioconductor.org/packages/Biostrings
[Category]: https://bioconductor.org/packages/Category
[ChIPseeker]: https://bioconductor.org/packages/ChIPseeker
[DESeq2]: https://bioconductor.org/packages/DESeq2
[GenomicRanges]: https://bioconductor.org/packages/GenomicRanges
[GenomicFiles]: https://bioconductor.org/packages/GenomicFiles
[GenomicFeatures]: https://bioconductor.org/packages/GenomicFeatures
[GOstats]: https://bioconductor.org/packages/GOstats
[Gviz]: https://bioconductor.org/packages/Gviz
[ReportingTools]: https://bioconductor.org/packages/ReportingTools
[ShortRead]: https://bioconductor.org/packages/ShortRead
[SummarizedExperiment]: https://bioconductor.org/packages/SummarizedExperiment
[VariantAnnotation]: https://bioconductor.org/packages/VariantAnnotation
[VariantFiltering]: https://bioconductor.org/packages/VariantFiltering
[VariantTools]: https://bioconductor.org/packages/VariantTools 
[biomaRt]: https://bioconductor.org/packages/biomaRt
[csaw]: https://bioconductor.org/packages/csaw
[edgeR]: https://bioconductor.org/packages/edgeR
[limma]: https://bioconductor.org/packages/limma
[rtracklayer]: https://bioconductor.org/packages/rtracklayer
[r5vc]: https://bioconductor.org/packages/r5vc
[WGCNA]: https://cran.rstudio.com/web/packages/WGCNA

[shiny]: http://shiny.rstudio.com/
[kallisto]: http://pachterlab.github.io/kallisto
