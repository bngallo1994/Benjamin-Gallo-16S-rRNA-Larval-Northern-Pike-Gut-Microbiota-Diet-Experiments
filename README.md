# Benjamin-Gallo-16S-rRNA-Larval-Northern-Pike-Gut-Microbiota-Diet-Experiments
Data files and associated R-Code for published data (Title of Publication TBD). Standard Operating Procedures for sample processing can be found in the SOP repository. Please email bngallo1994@gmail.com if you have any questions or concerns. Enjoy!


Weclome to the SOP Repository!

The data included in this repository pertains to the collection of samples and data analysis associated with the following publication:

Initial diet influences future development paths of gut microbiota in larval northern pike (Esox lucius)
B. D. Gallo, J. M. Farrell, & B. F. Leydet
Hydrobiologia (2023)
https://link.springer.com/article/10.1007/s10750-023-05266-8

Provided below is a quick guide for understanding the contents of this repository. Please contact me if you have any questions. Enjoy!

Ben


CONTENTS:

Folder: Benjamin-Gallo-16S-rRNA-Larval-Northern-Pike-Gut-Microbiota-Diet-Experiments-master

Folder: Northern Pike Diet Experiments (Published Data)
CH_2_ALL_ASV_TABLE.csv
  - Raw ASV table of CLEANED samples for downstream analysis. This .csv file pertains to samples BEFORE they were combined by identical SILVA genus taxonomy. See "CH_2_ALL_MASTER_FILE.Rmd" for more information.

CH_2_ALL_MASTER_FILE.Rmd
  - Rmarkdown file pertaining to all statistical analysis performed in the publication (exluding zooplankton supplementary data and map creation). All files are linked in the "Data_Files_Analysis_R_Code" folder in this repository.

CH_2_ALL_MASTER_FILE.html
  - .html of Rmarkdown file (see above).

CH_2_ALL_Metadata.csv
  - All cleaned samples metadata (e.g. week sample was taken & treatment).

CH_2_taxa.csv
  - All SILVA generated taxa information pertaining to samples (linked with ASV #).

LARVAL_DIET_SRAs_Information.docx
  - Information pertaining to Sequence Read Archive (SRA's) for all samples. SRA's will be released upon publication or by June 1st, 2020.

Folder: DADA2_filter_Protocols
  - Rmarkdown files and associated information linked with raw .fastq filtering to obtained cleaned ASV's. Most of this information closely follows the tutorial posted by Benjamin Callahan (https://benjjneb.github.io/dada2/tutorial.html) with slight modifications.
  - Note .fastq files are linked with SRA's and will be released upon publication or by June 1st, 2020.

Folder: Data_Files_Analysis_R_Code
  - All files pertaining to CH_2_ALL_MASTER_FILE.Rmd R-code. The pathways to each file are correct pertaining to the location of the file in this repository. File path may change when you download files to your own computer.
 
Folder: Non_R_Scripts
  - Contains a .txt file pertaining to how the rarefaction curves were created using created .biom files and .shared files through the BIOM project and Mothur.


