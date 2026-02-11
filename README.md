# data-afex-spiders-traits-paper
Data and Scripts: Nutrient Limitation and Amazonian Spiders


This repository contains data, analysis scripts, and supplementary materials for the study investigating how soil nutrient limitation in an Amazonian forest affects the development (size) and nutritional status (fat content) of two spider species: Spilasma duodecimguttata and Hingstepeira folisecens.


In the repository, we uploaded:


data/: Contains 6 CSV files with processed data for analysis.

scripts/: Suplementar_pub.Rmd (RMarkdown script for statistical analysis).

docs/: Supplementary_Information.pdf (Detailed methods and statistical reporting).


#---------------------------------#


DATASET DESCRIPTION

1. Fat Extraction Comparison (To confirm the effectiveness of the fat extraction procedure, S1 and S2)


Files: Comparison_fat_steps_spilasma.csv and Comparison_fat_steps_hings.csv


These files document the step-by-step weight changes during the fat extraction protocol.


STEP: Procedure stage (Pi: Initial weight with fat; P1: Weight after 1st extraction; P2: Weight after 2nd extraction).


WEIGHT: Mean of mass in grams at each specific step.


#---------------------------------#


2. Morphometric Data (Size)


Files: Size_Spilasma.csv and Size_Hingstepeira.csv


WIDTH_CEPHALOTHORAX: Cephalothorax width (mm) measured via Zeiss Discovery stereomicroscope.


STATUS/CONDITION: Integrity of the abdomen (used to exclude damaged specimens or those parasitized by wasp larvae). STATUS was used for S. duodecimguttata because some spiders were 'parasitized' and were removed too (by a parasitoid wasp larva).


#---------------------------------#


3. Nutritional Status (Fat Content)


Files: Fat_Spilasma.csv and Fat_Hingstepeira.csv


Weight1 (_1-3): Triple measurements before extraction.


Weight2 (_1-3): Triple measurements after 1st chloroform extraction.


Weight3 (_1-3): Triple measurements after 2nd chloroform extraction.


Mean_weight (_1-3): Mean weight of the triple measurements for each measurement step.


Residual_fat: Total fat mass (Initial Mean Weight - Final Mean Weight). 


Standard_residuals: Standardized residuals between fat  used as the primary response variable for nutritional condition.


#---------------------------------#


Column Names and Description


EXPEDITION: Identify of the collection expedition.


BLOCK / PLOT: Spatial identifiers based on the AFEX experiment design.


TRT: Experimental treatment applied.


P / N / CATIONS: "Binary indicators (1 = presence, 0 = absence) of nutrient addition."


COLLECTION_DATE: Date when the specimen was collected.


SEX / AGE: Biological status (Note: All analyzed individuals are adult females).


#---------------------------------#


Ensure you have R and RStudio installed.


All analyses can be reproduced by running Suplementar_pub.Rmd. Options for running the commands include clicking the Knit option or running chunk by chunk.


The script expects the data files to be in the same working directory or a same folder named.
