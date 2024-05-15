# Yarrowia Annotations

## Purpose
This repository is dedicated to creating a mapping between different gene ID systems and function annotations in *Yarrowia lipolytica*. It combines 

## Annotation output.
The notebooks in this project create **yarrowia_annotations_kegg_uniprot.xlsx**. It contains the mapping of gene IDs and gene functions from KEGG, UniProt, and JGI. Here are the first two rows of this file.

| JGI ID               | JGI Start | JGI End | NCBI Start | NCBI End | NCBI ID      | Column1     | NCBI        | KEGG Annotation | Uniprot Annotation                                                                                                                                                         | Uniprot Primary Accession |
|----------------------|-----------|---------|------------|----------|--------------|-------------|-------------|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| jgi.p\|Yarli1\|64471 | 2659      | 5277    | 2659       | 5277     | YALI0_A00110g | YALI0A00110g | YALI0A00110g | unknown function | oligopeptide transmembrane transporter activity [GO:0035673]                                                                                                                  | Q6CIA8                    |
| jgi.p\|Yarli1\|64472 | 7045      | 8880    | 7045       | 8880     | YALI0_A00132g | YALI0A00132g | YALI0A00132g | K03283 heat shock 70kDa protein 1/2/6/8 | ATP binding [GO:0005524]; ATP hydrolysis activity [GO:0016887]; ATP-dependent protein folding chaperone [GO:0140662]; heat shock protein binding [GO:0031072]; protein folding chaperone [GO:0044183] | Q6CIA7                    |

## Data Sources
- [KEGG Annotations](https://www.genome.jp/dbget-bin/www_bfind_sub?mode=bfind&max_hit=1000&locale=en&serv=gn&dbkey=yli&keywords=YALI0&page=1): The data from 8 pages was combined into this file.
- [UniProt Annotations](https://www.uniprot.org/uniprotkb?query=%28taxonomy_id%3A4952%29): This file was produced using the 'download' button and selecting .tsv format.
- **yarrowia_annotations.csv**: This file is believed to have been provided by JGI.