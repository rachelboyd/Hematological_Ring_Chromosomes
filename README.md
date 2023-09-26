# Ring_Chromosome
Analysis pipeline and figure generation for "Paper Title"

DIRECTORY

kar_analysis_raw.xls: This is a raw data file containing patient ID, karyotype information, neoplasia subtype, and identified mutations in known cancer genes. This is the raw data that gets cleaned and wrangled using Cyto_Parse_Script.Rmd.

Scripts (Folder):
-  Cyto_Parse_Script.Rmd : This reformats, cleans, and structures kar_analysis_raw.xls data. This script generates multiple indermediate files for analysis, as well as "filtered_data.xlsx," which is the dataset that gets read into Lymphoid_Myeloid_Analysis.Rmd.
- Lymphoid_Myeloid_Analysis.Rmd : This script analyzes "filtered_data.xlsx," by splitting it by myeloid and lymphoid malignancies. This is the script that generates all of the figures found in the "Figures" folder.
  
Figures (Folder):
- All figures generated using Lymphoid_Myeloid_Analysis.Rmd.
