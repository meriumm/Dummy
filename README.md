# Dummy Repository

This is the dummy repository to demonstrate directory structure, file
trees, linking dios, and editing a README.md file

# DOI

[![DOI](https://zenodo.org/badge/939506658.svg)](https://doi.org/10.5281/zenodo.14933235)

## Link to the analysis

- [Analysis 1](01_Analysis./01_Script.md)
- [Analysis 2](02_Analysis/02_Script.md)

## File Tree

``` r
fs::dir_tree()
```

    ## .
    ## ├── 01_Analysis
    ## │   ├── 01_Script.docx
    ## │   ├── 01_Script.html
    ## │   ├── 01_Script.md
    ## │   ├── 01_Script.pdf
    ## │   ├── 01_Script.Rmd
    ## │   └── TipsR.csv
    ## ├── 02_Analysis
    ## │   ├── 02_Script.docx
    ## │   ├── 02_Script.html
    ## │   ├── 02_Script.md
    ## │   ├── 02_Script.pdf
    ## │   └── 02_Script.Rmd
    ## ├── Dummy.Rproj
    ## ├── README.docx
    ## ├── README.html
    ## ├── README.md
    ## ├── README.pdf
    ## ├── README.Rmd
    ## └── README_files
    ##     └── figure-gfm
    ##         └── pressure-1.png

``` bash

├── 01_Analysis
│   ├── 01_Script.docx
│   ├── 01_Script.html
│   ├── 01_Script.md
│   ├── 01_Script.pdf
│   ├── 01_Script.Rmd
│   └── TipsR.csv         #Data Descriptionnfor analysis part 1 read into 01_script.Rmd
├── 02_Analysis           #Analysis Directory
│   ├── 02_Script.docx
│   ├── 02_Script.html
│   ├── 02_Script.md     #Github formatted Markdown
│   ├── 02_Script.pdf
│   └── 02_Script.Rmd
├── Dummy.Rproj         # Top level directory . Rproj file = working directory
├── README.docx
├── README.html
├── README.md
├── README.pdf
├── README.Rmd            # Top level directory README
└── README_files
    └── figure-gfm
        └── pressure-1.png
```
