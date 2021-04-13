## Lab journal for courses in [Bioinformatics Institute](https://bioinf.me/education/program/)

Entries organized as `PROJECT_NAME/YYYY_MM_DD.md`

## Reports
* [Causes of the E.Coli outbreak in Germany in April 2011.](https://github.com/DespairedController/bioinf_lab_journal/blob/main/E_COLI_OUTBREAK/What%20caused%20an%20E.%20Coli%20outbreak.pdf)
* [Mutations that probably cause ampicillin resistance in E.Coli.](https://github.com/DespairedController/bioinf_lab_journal/blob/main/ANTIBIOTIC_RESISTANCE/Mutations%20that%20probably%20cause%20ampicillin%20resistance%20in%20E.Coli..pdf)

## Project description
### ANTIBIOTIC_RESISTANCE
#### “What causes antibiotic resistance?” Alignment to reference, variant calling
The goals are to analyze that sequencing data from a strain of E. coli resistant to the antibiotic ampicillin to locate the mutations responsible for giving E. coli its antibiotic resistance property, to research the genes that are mutated to identify the mechanism of antibiotic resistance in each case, and to make recommendations for alternative antibiotics a doctor could use to treat each strain.

#### Plan
1. Get data
2. Inspect raw sequencing data manually
3. Inspect raw sequencing data with fastqc.
4. Filtering the reads.
5. Aligning sequences to reference
6. Variant calling
7. Variant effect prediction
8. Writing lab report

### E_COLI_OUTBREAK
#### "E. coli outbreak investigation". De novo assembly and annotation of bacterial genomes.
The goal is to reproduce part of [E. coli O104:H4 Genome Analysis](https://github.com/ehec-outbreak-crowdsourced/BGI-data-analysis/wiki) on TY2482 sequencing data and answer following questions:
1. What is genomic sequence of E.Coli X?
2. What strain of E. coli is E. coli X most similar to? (Where did it come from?)
3. What are the genes that E. coli X contains?
4. Which of these genes make E. coli X distinct?
5. How did E. coli X evolve to obtain these genes?
6. How did E. coli X become pathogenic?

#### Plan
1. Explore the dataset with FastQC
2. K-mer profiling and genome size estimation
3. Assembling E.Coli X genome from paired reads
4. Analyze effect of read correction
5. Analyze impact of reads with large insert size
6. Genome annotation
7. Finding the closest relative of E.Coli X
8. Finding what is the genetic cause of HUS
9. Tracing the source of toxin genes in E.Coli X
10. Antibiotic resistance detection
11. Writing lab report
