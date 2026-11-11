# Ibrahim Marube

MSc Bioinformatics student at the University of Potsdam. I'm learning genome annotation
and sequence bioinformatics by building small, reproducible benchmarks on the university
HPC cluster and checking every result against curated reference annotations.

## Projects

**[genome-annotation-benchmarks](https://github.com/Ibrahim-Marube/genome-annotation-benchmarks)**
Ab initio gene finders compared against RefSeq on *E. coli* K-12: Prodigal found 96.0% of
reference genes and Glimmer3 94.5%, but their start sites agree with RefSeq in 90.5% and
71.3% of genes. Snakemake workflow, error analysis of the misses and extras, verified
from a fresh clone.

**[plastome-annotation-benchmark](https://github.com/Ibrahim-Marube/plastome-annotation-benchmark)**
Reference-based plastome annotation (PGA) scored against the RefSeq annotation of
*Medicago truncatula*, with three references of different relatedness. With RefSeq
references as downloaded, PGA silently skipped every rRNA and almost every tRNA (66-70% of
genes found); renaming genes to the convention PGA expects raised that to 93.6-94.5%.
Also tracked down a bug in PGA's temporary file names that made about 1 run in 8 silently
produce an unannotated result.

## Tools

Snakemake, Python, Bash, Git, SLURM / environment modules, BLAST+, Prodigal, Glimmer3, PGA.
