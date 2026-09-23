# Advances in Microbial Genomics and Bioinformatics — Tutorials

Hands-on tutorials introducing high-throughput sequencing (HTS) bioinformatics, built
around real microbial datasets. Each tutorial assumes and reuses skills from the previous
one, so working through them in order is recommended.

Start with Tutorial 1 whatever your background — it sets up every tool the others rely on.

| # | Tutorial | Theme |
|---|----------|-------|
| 1 | [Setting the Stage](docs/t1-setting-the-stage.md) | Environment setup: VMs/WSL, Miniconda, R/RStudio |
| 2 | [Somethings about Qualities](docs/t2-qualities.md) | QC & read filtering (short + long reads, incl. falco) |
| 3 | [Somethings about Genome Assemblies](docs/t3-assemblies.md) | Long-read assembly, polishing, annotation |
| 4 | [Reference Alignment & breseq](docs/t4-reference-alignment-breseq.md) | Short-read mapping, coverage, SNVs, breseq |
| 5 | [Somethings about Sanger](docs/t5-sanger.md) | Sanger trace processing, merging, BLAST |
| 6 | [Intro to Metabarcoding](docs/t6-metabarcoding.md) | Amplicon analysis (DADA2 + phyloseq, in R) |

## Datasets

The sequencing data is not in this repository. It is archived on Zenodo, and each tutorial
states which ZIP file it needs:

**https://doi.org/10.5281/zenodo.20569025**

## Requirements

A working **Miniconda** install, and **R/RStudio** for Tutorials — both covered
in Tutorial 1. Comfort with the Linux command line helps but isn't assumed; each tutorial
gives the hints you need.

## License

Prose, figures and screenshots: [CC BY 4.0](LICENSE) — reuse freely with attribution.
