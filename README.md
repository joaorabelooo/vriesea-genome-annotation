# vriesea-genome-annotation
Genome annotation datasets and functional analyses for Vriesea species (V. longistaminea and V. minarum).
# Vriesea Genome Annotation

Chromosome-scale genome annotation and functional datasets for two threatened *Vriesea* species.

---

## Study system

*Vriesea longistaminea* (Critically Endangered) and *Vriesea minarum* (Endangered) are two bromeliad species endemic to Brazil, both restricted to rocky montane ecosystems within the Brazilian Iron Quadrangle. These environments are characterized by nutrient-poor substrates and intense anthropogenic pressure, particularly from mining activities.

Due to their narrow distribution and ecological specialization, these species represent valuable models for investigating genome evolution, adaptation to extreme edaphic conditions, and conservation genomics in Neotropical plants.

---

## Dataset description

This repository provides genome annotation resources for *Vriesea longistaminea* and *Vriesea minarum*. The dataset includes structural and functional genome annotations derived from chromosome-scale, haplotype-resolved genome assemblies.

Gene models were predicted using BRAKER3 with RNA-seq evidence and soft-masked genomes, and subsequently filtered to retain the longest isoform per gene. Functional annotation was assigned based on homology searches and protein domain identification using eggNOG-mapper and InterProScan.

---

## Available files

For each species, the following files are provided:

- GFF3 file containing structural and functional genome annotations  
- Protein sequences (.faa) corresponding to predicted gene models  
- Coding sequences (.fna) of predicted CDS  
- Tabular file summarizing functional annotations for each gene  

All files are organized by species and formatted for immediate reuse.

---

## Repository structure
