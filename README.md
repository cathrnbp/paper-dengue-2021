# Retrospective Genomic Characterization of a 2017 Dengue Virus Outbreak, Burkina Faso

This repo holds data used in the manuscript: 
Letizia AG, Pratt CB, Wiley MR, Fox AT, Mosore M, Agbodzi B, et al. Retrospective Genomic Characterization of a 2017 Dengue Virus Outbreak, Burkina Faso. Emerg Infect Dis. 2022;28(6):1198-1210. https://doi.org/10.3201/eid2806.212491

### BEAST analysis
All whole genome sequences were downloaded from [ViPR](https://www.viprbrc.org/brc/vipr_genome_search.spg?method=ShowCleanSearch&decorator=flavi_dengue) trimmed to the coding sequence for each dengue virus serotype, 10% randomly subsampled and all Africa-origin sequences retained. Sequences were aligned and xml files generated for use with [BEAST](https://beast.community/index.html)
- DENV1_subset.fasta
- DENV2_subset.fasta
- DENV3_subset.fasta
- DENV1_subset.xml
- DENV2_subset.xml
- DENV3_subset.xml

### E gene sequences
All sequences were downloaded from [ViPR](https://www.viprbrc.org/brc/vipr_genome_search.spg?method=ShowCleanSearch&decorator=flavi_dengue), aligned and trimmed to the E-gene.
- DENV1_Egene.fasta
- DENV2_Egene.fasta
- DENV3_Egene.fasta

### Amino acid alignments
All sequences were downloaded from [ViPR](https://www.viprbrc.org/brc/vipr_genome_search.spg?method=ShowCleanSearch&decorator=flavi_dengue), aligned, trimmed to the prME region, and translated to amino acid.
- DENV1_prME_aa.fasta
- DENV2_prME_aa.fasta
- DENV3_prME_aa.fasta
