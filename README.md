# Applied Computational Genomics Course at UU: Spring 2017
- Aaron Quinlan
- Full semester course, Tu/Th
- January 9 - April 25
- 2 credit hours
- http://mcb112.org/

# Overview
This course will provide a comprehensive introduction to fundamental concepts and experimental approaches in the analysis and interpretation of experimental genomics data. It will be structured as a series of lectures covering key concepts and analytical strategies. A diverse range of biological questions enabled by modern DNA sequencing technologies will be explored including sequence alignment, the identification of genetic variation, structural variation, and ChIP-seq and RNA-seq analysis. Students will learn and apply the fundamental data formats and analysis strategies that underlie computational genomics research. The primary goal of the course is for students to be grounded in theory and have the ability to conduct independent genomic analyses.

# Prerequisites
- Online introduction to Linux. Students must complete the following two online tutorials before class begins. If they don't things will be very complicated very quickly.
  - https://www.codecademy.com/en/courses/learn-the-command-line/lessons/environment/exercises/bash-profile
  - http://korflab.ucdavis.edu/Unix_and_Perl/current.html#part1 
- An Apple computer or a windows machine with Putty installed.
- Need TAs
- Need to put together a homogenous computing environment for the students to use

# Other ideas
- Lecture on the history of computational biology - with a focus on genomics.

# Syllabus
- **Lecture 0: A brief history of human evolution**
    - Pre-human history
    - Out of africa
    - Explosive population growth
    - 30 generations ago, 2^30: 1066 AD. A billion ancestors is more than the entore population then.
    - Genetic variation: shared versus individual
    - Hands of cards analogy
    - The effect of recombination and sexual reproduction
    - Mutation
    - Explosive population growth
- **Lecture 1 (Tu Jan 10; Quinlan): What is a genome?**
    - Focus on the human genome
    - Chromosomes
    - Repeats
    - Mobile elements
    - Genes
    - Chromatin
    - Chromatin modifications
    - Transcripts
    - Promoters
    - Enhancers
    - Transposons
    - Genome regulation
    - Genome architecture
- **Lecture 2 (Th Jan 12; Quinlan): Using UNIX to find patterns in a genome**
    - pattern matching
    - head
    - grep
    - cut
    - sort
    - uniq
    - basic regular expressions
    - Homework (due Jan 17)
- **Lecture 3 (Tu Jan 17; Quinlan): Mutation, genetic variation, selection, and drift**
    - What is a mutation? Mechanisms
    - Polymorphism
    - SNPs
    - INDELs
    - SV and CNV
    - Landscape of human genetic variation
    - Selection and drift
    - Homework (due Jan 24)
- **Lecture 4 (Th Jan 19; Quinlan): Modern DNA sequencing technologies and applications**
- **Lecture 5 (Tu Jan 24; Quinlan): Detecting genetic variation, part 1**
    - FASTQ
    - Sequence alignment
        - Theory
        - Tools
    - SAM/BAM format
    - SamTools and IGV
    - Homework (due Jan 26)
- **Lecture 6 (Th Jan 26; Marth): Detecting genetic variation, part 2**
    - SNP and INDEL calling
        - Theory
            - Bayes theorem
            - PolyBayes
        - Tools
    - Assigning a genotype
    - Common problems and artifacts
        - paralogy
        - low depth
        - high error rate
        - ambiguous alignment
    - Single sample detection
    - Families
    - Population calling
- **Lecture 7 (Tu Jan 31; Quinlan): Detecting genetic variation, part 2**
    - Structural and copy number variation
- **Lecture 8 (Th Feb 2; Quinlan): Detecting genetic variation, part 3**
    - VCF format
        - Attributes
        - Genotypes
    - Exploring the format
        - examples
        - IGV
    - Manipulating VCF with bcftools
    - Homework (due Feb 2)
- **Lecture 9 (Tu Feb 7; Quinlan): Annotating genetic variation**
    - Concepts
        - e.g, synonymous, non-synonymous
        - frameshift
        - stopgain
        - conservation
    - Tools
        - Polyphen
        - CADD
        - VEP
        - SnpEff
    - Homework (due Feb 2)
- **Lecture 10 (Th Feb 9; Quinlan): Prioritizing genetic variation in studies of disease**
    - Mendelian disease focus
    - Inheritance patterns
    - Population frequency
    - Functional consequence
- **Lecture 11 (Tu Feb 14; Yandell): Genome annotation**
    - How and why do we annotate a genome?
    - Repeatmasker
    - Gene models
    - MAKER
- **Lecture 12 (Th Feb 16; Quinlan): Genome data formats and genome arithmetic**
    - The genome as a coordinate system
    - BED format
    - GFF format
    - Recap BAM format
    - Concepts of genome arithmetic
    - Applications of genome arithmetic
    - UCSC for viz
- **Lecture 13 (Tu Feb 21; Quinlan): Applied genome arithmetic with bedtools**
    - Homework (due Feb 21)
- **Lecture 14 (Th Feb 23; Quinlan): Identifying statistically significant relationships among genome interval sets**
    - Homework (due Feb 23)
- **Lecture 15 (Tu Feb 28; Quinlan): Digging deeper into UNIX, part 1**
    - more useful commands
    - applied examples
- **Lecture 16 (Th Mar 2; Quinlan): Digging deeper into UNIX, part 2**
    - pipes
    - basic scripts and pipelines
    - basic math and stats on the command line
    - Homework (due Mar 7)
- **Lecture 17 (Tu Mar 7; Quinlan): ChIP-seq principles**
    - experimental design
    - protocols
    - examples
- **Lecture 18 (Th Mar 9; Quinlan): ChIP-seq analysis**
    - analyses
    - toolsets
    - Homework (due Mar 14)
- **Lecture 19 (Tu Mar 14; Quinlan): RNA-seq principles**
    - experimental design
    - protocols
    - examples
- **Lecture 20 (Th Mar 16; Quinlan): RNA-seq analysis**
    - analyses
    - toolsets
    - Homework (due Mar 21)
- **Lecture 21 (Tu Mar 21; Quinlan): Basic probability**
    - Probability with coins and dice
    - Probability with DNA
    - Conditional probabilities
    - Use R for examples
    - Homework (due Mar 23)
- **Lecture 22 (Th Mar 23; Quinlan): Probability distributions**
    - Binomial
    - Gaussian
    - Poisson
    - Applications
- **Lecture 23 (Tu Mar 28; Quinlan): Data visualization, part 1**
    - Why
    - Pattern recognition
    - Detect problems
    - Ansombe’s quartet
- **Lecture 24 (Th Mar 30; Quinlan): Data visualization, part 2**
    - http://www.nature.com/collections/qghhqm/pointsofsignificance
    - Scatter plots
    - Histograms
    - Box whiskers
- **Lecture 25 (Tu Apr 4; Quinlan): Class project introduction: identifying and characterizing de novo mutations in genomes**
    - work in pairs
    - de novo mutation and human disease
    - Project (due Apr 25)
        - introduce problem and dataset
            - dataset with 4 families of 4
            - they must find the mutation causing a different disease phenotype in each family
- **Lecture 26 (Th Apr 6; Quinlan): Class project**
    - Introduction to gemini
    - Hands on
- **Lecture 27 (Tu Apr 11; Quinlan): Class project**
    - Gemini de novo tutorial, Q and A
- **Lecture 28 (Th Apr 13; Quinlan): Class project**
    - OMIM
    - ClinVar
    - ExAC
- **Lecture 29 (Tu Apr 18; Quinlan): Class project**
    - Common artifacts in identifying de novo mutations
    - Mutation versus polymorphism
- **Lecture 29 (Th Apr 20; Quinlan): Class project**
    - Questions, group discussion
- **Lecture 30 (Tu Apr 25; Quinlan): Final class**
    - Group presentations
    - Class evaluations
