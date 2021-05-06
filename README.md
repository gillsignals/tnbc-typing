# tnbc-typing

Cleaned code for my final project in Advanced Topics in Genomic 
Data Analysis (JHU, Spring 2021), analyzing replicability of 
scRNA-seq cell typing of triple negative breast cancer (TNBC) 
from Karaayvaz et al., 2018.

## Components

- `tnbc-typing-master-script.Rmd`: Single script that runs the entire analysis. Assumes GEO `.txt` data are stored in `data/` and `.rda` files are stored in `rdata/`.
- `data/`: Directory for tab-delimited `.txt` files downloaded from GEO. Note that these files are too large to store on GitHub, but directions for downloading them are in `tnbc-typing-master-script.Rmd`.
- `rdata/`: Directory for `.rda` files created to store objects from the analysis.
- `scripts/`: Directory for component scripts used to build the master script. *IMPORTANT: these scripts were originally run in the same directory as the txt and rda data files. Use the master script instead for compatibility with current file structure, or ensure files are in the intended location.*
