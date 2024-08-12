# Collision analysis on nanoCT data
Contains R scripts for analyzing and classifying single-cell nanoCT data. 
The main goal is to identify cell collisions in human-mouse Barnyard experiments by comparing the number of reads mapped to each species.

# Scripts
"barnyard_collisions.Rmd": input is single modality metadata 
"barnyard_collisions_multimodal.Rmd": input is merged metadata files from two modalities

# Packages
- mclust
- ggplot2
- dplyr
- mixsmsn
- tidyr