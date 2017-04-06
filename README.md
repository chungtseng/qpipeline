qpipeline
=========

**_qpipeline_** is a collection of utils for Next Gen Sequencing (NGS) data.  **_qpipeline_** is designed to be simple and easy to use and is written for processing the many file formats used in bioinformatics.  The primary goals of **_qpipeline_** are:  
1. flexible
2. reusable
3. reproducible
4. fast
5. and equally important, allows users to quickly extract and combine data from a large number of samples for further downstream analysis.

## INSTALLATION
see [installation instructions](INSTALLATION.md)
## USAGE
**_qpipeline_** is designed to work with different file formats.  Run **_qpipeline_** by itself to see what file formats currently supported
```
Written by Quang M Trinh <quang.trinh@gmail.com>. 

A collection of utils for Next Gen Sequencing (NGS) data.

Usage:
        qpipeline txt 
        qpipeline fasta
        qpipeline fastq
        qpipeline tabix
        qpipeline vcf 
```

Each file format has multiple modes supporting different functions.  For example, **_qpipeline tabix_** currently supported two functions: (1) annotating a VCF file against a BED database file; and (2) annotate a VCF file against a VCF database file.
```
Written by Quang M Trinh <quang.trinh@gmail.com>. 

Utils for annotating VCF files using tabix.

        qpipeline tabix [ -m mode ]  [ options ]

        -m 2000 annotate a VCF file against a BED database file.
        -m 2020 annotate a VCF file against a VCF database file.
```
