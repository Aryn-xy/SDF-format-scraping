# Scraping SDFs from PubChem
This project contains an R script that reads an Excel file containing phytochemical names from Rosmarinus officinalis and automatically downloads their corresponding SDF (Structure Data File) from PubChem. Each SDF file is saved in a dedicated folder. The script retrieves SDF files from PubChem using compound names from an Excel file.

## Dependencies

- **httr**: For making HTTP requests to PubChem.
- **readxl**: For reading the Excel file.
- **writexl**: For writing Excel files.
- **stringr**: For safe filename creation.

You can install these packages by running:

```r
install.packages(c("httr", "readxl", "writexl", "stringr"))
```


