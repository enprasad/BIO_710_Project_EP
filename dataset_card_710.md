---
editor_options: 
  markdown: 
    wrap: 72
---

# BIO_710_Project_EP

## Supported Tasks

### Task Category

heatmap-generation, dataset-wrangling, gene-correlation

## Languages

Monolingual - English

### Dataset Creators

Emma Bryer, Esha Prasad, Jose de la Torre, Gillyan Valencia

### Data Origins and Formatting

This data comes from a larger relative abundance data set. This data set was then put under the limitations of having an rpkg (reads per kilobase per gigabase) of 0.1. This meant that these organisms were relatively abundant at at least one site. This dataset consists of around 1200 organisms. It was later made into a database using Kraken-2. 

The mock dataset was generated using organisms identified through a heatmap, and genes were chosen based on identified KEGG pathways.

### Data Format

All data is present in CSV format, and there is one for relative abundance and another for genes and gene count. 

### Data Collection

Our lab data is generated first through sediment collection, where we go to our hot spring, Great Boiling Spring (GBS), in Nevada. We collect only about 1-2 cm of the top layer of sediment, and try to make sure that very little water is mixed with the sediment. We collect sediment from 4 sites (A, B, C, E) and one water sample through tangential flow filtration (TFF), which concentrates the amount of organisms in the water. These samples are put on dry ice and taken to the lab where they are then put through a DNA extraction using chloroform, which is common when doing high-molecular-weight extractions. We try to ensure that the DNA we extract is as long as possible. Afterwards, it is sent off to undergo Illumina sequencing, which then returns to us as FASTA files. We use these FASTA files to make metagenome assembled genomes (MAGs) that are representative of the organisms in our hot spring. These MAGs can then be used to make things like the Kraken-2 database we haave constructed. 

## Size Category

1K\<n\<10K

## Tags

bioinformatics;genome-analysis, microbio;dna-sequencing
