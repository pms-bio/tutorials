# Advances in Microbial Genomics and Bioinformatics — Tutorials

Hands-on tutorials introducing high-throughput sequencing (HTS) bioinformatics, built around real microbial datasets. Each tutorial assumes and reuses skills from the previous one, so working through them in order is recommended.

## Tutorials

| # | Tutorial | Theme |
|---|----------|-------|
| 1 | [Setting the Stage](t1-setting-the-stage.md) | Environment setup: VMs/WSL, Miniconda, R/RStudio |
| 2 | [Somethings about Qualities](t2-qualities.md) | QC & read filtering (short + long reads) |
| 3 | [Somethings about Genome Assemblies](t3-assemblies.md) | Long-read assembly, polishing, annotation |
| 4 | [Reference Alignment & breseq](t4-reference-alignment-breseq.md) | Short-read mapping, coverage, SNVs, breseq |
| 5 | [Somethings about Sanger](t5-sanger.md) | Sanger trace processing, merging, BLAST |
| 6 | [Intro to Metabarcoding](t6-metabarcoding.md) | Amplicon analysis (DADA2 + phyloseq, in R) |

**Planned follow-ups:** comparative/functional genomics · shotgun metagenomics · reproducible-workflows capstone.

## Audience & prerequisites

- Aimed at learners new to bioinformatics; comfort with the Linux command line helps but isn't required (each tutorial gives the hints you need).
- You'll need a working **Miniconda** install and, for some tutorials, **R/RStudio** — both covered in Tutorial 1.

## Conventions

- Commands appear in code blocks with a **copy button** (top-right) — use it instead of selecting text, to avoid copy-paste errors.
- `> **Note:**` / `> ⚠️` callouts highlight important points and pitfalls.
- `[Q#]` prompts are discussion/self-assessment questions.
