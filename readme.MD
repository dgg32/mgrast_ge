

# Introduction

  

  

This repository contains code and data for my article "[Control Data Quality in Sequencing Projects with Great Expectations](https://dgg32.medium.com/control-data-quality-in-sequencing-projects-with-great-expectations-1a321d1e4fef)".

1. The api_investigate.ipynb is for downloading data from MG-RAST.

2. The tsv data folder contains the TSV to be check by Great Expectations. I have added a test file for each type so you can test your GE on some other data.

3. The fasta data folder contains the fasta files from the MG-RAST projects. For simplicity, only the first 100 sequences are kept for each project.

  

# Prerequisite

Great Expectations
  

# Run

The data folder contain some example data. If you want to download the your own data, open api_investigate.ipynb and modify the project list, and run the cells

The seq_article.ipynb runs GE on the sequence statstics file.

The meta_article.ipynb runs GE on the metadata file.

Thew meta_ge.ipynb and seq_ge.ipynb are alternative ways to run GE on the same files.


## Authors

  

*  **Sixing Huang** - *Concept and Coding*

  

## License

  

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
