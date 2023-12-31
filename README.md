# R scripts for processing and analysis of 16S amplicon sequences, Biolog EcoPlates, and environmental data
This respository contails R scripts for sequence processing and analysis of 16S amplicon data, Biolog EcoPlate data, and corresponding environmental data from a High Arctic tidal flat.

## Manuscript_Script_Cleaned.Rmd
This script is for processing 16S amplicon data with DADA2 to generate an ASV table, filtering with phyloseq, inferring functions with Tax4Fun, and processing environmental data. Tables produced are used for plotting in `Manuscript_Plots.Rmd`. 

## Plate_Processing_Cleaned.Rmd
This script is for processing Biolog EcoPlate absorbance data. Tables are produced for plotting in `Manuscript_Plots.Rmd`. 

## Manuscript_Plots.Rmd
This script is for producing all the plots and statistical analyses in "Seasonality in land-ocean connectivity and local processes control sediment bacterial community structure and function in a high Arctic tidal flat". It uses tables produced in the two scripts above. 

## Other

**silva_nr99_v138.1_wSpecies_train_set.fa.gz** is the file used for assigning taxonomy in the Manuscript_Script_Cleaned.Rmd script. It was downloaded from DADA2's GitHub repository: <https://benjjneb.github.io/dada2/training.html>

:exclamation: These files are optimized for the studied environmental system and are dependant on metadata of the system. The scripts are meant for replication of the following published study: <https://doi.org/10.1093/femsec/fiad162>

:dna: The original sequencing data has been archived at NCBI's Sequence Read Archive under BioProject accession PRJNA1054200. The processed tables (output of Manuscript_Script_Cleaned.Rmd and Plate_Processing_Cleaned.Rmd) are available at the Northeastern University Digital Repository Service: <http://hdl.handle.net/2047/D20621103>.

:question: Please let me know if you encounter any problems or have any questions.
