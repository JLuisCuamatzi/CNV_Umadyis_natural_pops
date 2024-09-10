# Identification of large copy number variants in <i>Ustilago maydis</i> isolates

In this project, I used the sequencing data of fifty <i>U. maydis</i> isolates published in the next two papers:
 - [Population Genomics of the Maize Pathogen Ustilago maydis: Demographic History and Role of Virulence Clusters in Adaptation](https://academic.oup.com/gbe/article/13/5/evab073/6219951?login=false)
    - The research conducted by Schweizer <i>et al</i>., 2021 encompass 22 isolates from different locations of Mexico
 - [Effectors with Different Gears: Divergence of Ustilago maydis Effector Genes Is Associated with Their Temporal Expression Pattern during Plant Infection](https://www.mdpi.com/2309-608X/7/1/16)
    - The research conducted by Depotter <i>et al</i>., 2021 includes a total of 28 isolates from Europe and China

The genome [<i>U. maydis</i> 521 v.2.0](https://fungi.ensembl.org/Ustilago_maydis/Info/Index) was used as reference genome for the subsequently analysis.

## 01. Fastq Files Download
The fastq files were download from the NCBI by accessing the BioProject [PRJNA674756](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA561077) Depotter <i>et al</i>., 2021 and [PRJNA561077](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA561077) for Schweizer <i>et al</i>., 2021.

## 02. Cleaning and Mapping
The fastq files were processed with the <i>pipeline</i> reported by [Cuamatzi-Flores <i>et al</i>., 2024](https://link.springer.com/article/10.1007/s10123-024-00489-8) available at [USMA_H2O2_Adaptation](https://github.com/JLuisCuamatzi/USMA_H2O2_Adaptation/tree/main).
 
## 03. Identification of Copy Number Variants by Analyzing the Normalized Coverage


