# tnbc-typing

Cleaned code for my final project in Advanced Topics in Genomic 
Data Analysis (JHU, Spring 2021), analyzing replicability of 
scRNA-seq cell typing of triple negative breast cancer (TNBC) 
from Karaayvaz et al., 2018.

## Components

- `tnbc-typing-master-script.Rmd`: Single script that runs the entire analysis. Assumes GEO `.txt` data are stored in `data/` and `.rda` files are stored in `rdata/`.
- `data/`: Tab-delimited `.txt` files downloaded from GEO ([GSE118389](https://www-ncbi-nlm-nih-gov.proxy1.library.jhu.edu/geo/query/acc.cgi?acc=GSE118389)). Note that these files are too large to store on GitHub, but directions for downloading them are in `tnbc-typing-master-script.Rmd`.
- `paper/`: PDFs of the original paper and supplement.
- `rdata/`: Directory for `.rda` files created to store objects from the analysis.
- `report/`: Word and PDF versions of the final report and interim report, as well as final figures.
- `results/`: Output `.png` images produced by the master script.
- `scripts/`: Component scripts used to build the master script. *IMPORTANT: these scripts were originally run in the same directory as the txt and rda data files. Use the master script instead for compatibility with current file structure, or ensure files are in the intended location.*
- `slides/`: Powerpoint and PDF versions of slides from the in-class final presentation.
