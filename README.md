# UK Crop Microbiome Cryobank
## Agmicrobiomebase

This repository contains the scripts to process the fastq sequence files from the 16S and ITS amplicon Illumina sequencing and for the metagenomic Illumina sequencing for the UK Crop Microbiome Cryobank Project.

The UK Crop Microbiome Cryobank integrates genomic (DNA) data with a cryobank collection of samples for the soil microbiomes of the UK major crop plant systems. 
For this project, the microbiomes are from the rhizosphere (the soil surrounding the crop plant roots) and from bulk soil (soil outside the rhizosphere). 
The Cryobank provides a facility for researchers to source data and samples, including cryo-preserved microbial material and genomic and metagenomic sequences from different soil microbiome environments. 

The project has sequenced soil microbiomes from 6 different UK crops grown in 9 different soil types (within a pot experiment) from across the United Kingdom.

The data catalogue for this project can be accessed at https://agmicrobiomebase.org/. 
The catalogue links the raw sequence data files which have been submitted to the European Nucleotide Archive (ENA) with soil metadata.

This repository contains procedural information and scripts for 
1. Analysis of **16S Amplicon** sequence fastq files to derive amplicon sequence variant taxonomies using qiime2
- 16S-sequence-analysis.md: markdown file describing all processing steps: from fastq to asv taxa output file
- 16S-script-startup-1 : script to install software and set-up environments and downloaded databases
- 16S-script-preprocessing-2 : script to trim reads
- 16S-script-qiime2
- README.md
    
2. Analysis of **ITS amplicon** fastq sequence files to derive amplicon sequence variant taxonomies using qiime2
- ITS-sequence-analysis.md: markdown file describing all processing steps: from fastq to asv taxa output file
- ITS-script-startup-1 : script to install software and set-up environments and downloaded databases
- ITSS-script-preprocessing-2 : script to trim reads
- ITSS-script-qiime2
- README.md
3. Preparation and mapping of **amplicon sequence data for submission to ENA using standard templates** for intercative submission via the WebinPortal (https://www.ebi.ac.uk/ena/submit/webin/login)
- ENA-upload-procedure.md
- ENA sample template example for one crop
- ENA fastq template example for one crop
- ENA ERS output exmaple file for one crop
- R-code to map ERS numbers from sample uplaods to fastq template
- README.md  
4. **Pre-processing of metagenomic sequence data**
- procedure.md
- scripts
- README.md  
5. Preparation and mapping of **metagenomic sequence data for submission to ENA using standard templates** for intercative submission via the WebinPortal (https://www.ebi.ac.uk/ena/submit/webin/login)
- procedure.md
- scripts
- README.md  
6. Processing of **amplicon sequence data for 3 case studies** in the Crop Microbiome Cryobank Publication 1  
- Case Study A-Influence of soil type  
  -- procedure.md  
  -- scripts  
  -- README.md  
- Case Study B The core Microbiome  
  -- procedure.md  
  -- scripts  
  -- README.md  
- Case Study C ITS taxonomy and Fusarium in wheat  
  -- procedure.md  
  -- scripts  
  -- README.md  
7. **R code to create figures** for UK Crop Microbiome Cryobank Publication 1  
  -- scripts  
  -- README.md  

