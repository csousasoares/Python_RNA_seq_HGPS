# (Python) Transcriptome Analysis of HGPS Fibroblasts Treated with UMK57

Repository reproducing, in Python, multiple analyses in the manuscript "Small-molecule 
targeting of kinesin-13 KIF2C enhances double-strand break DNA repair and 
slows down aging". 

Analyses can be visualized in the Jupyter Notebook (just open the .ipynb file).

This was done to test my ability to perform RNA-seq analysis (DESeq2, GSEA, etc.) in Python,
since this language is increasingly used in bioinformatics pipelines.

## Installation

The environment is specified in the environment.yml file. To restore the environment, just do:

```bash
conda env create -f environment.yml
conda activate bioinformatic_analyses
```

## Directory Structure

```
project_root/
├── input_data/
│   ├── counts_matrix.csv
│   └── sample_info.csv
└── output_data/
```

## Usage

After activating the environment, launch Jupyter and open the notebook:

```bash
jupyter lab hgps_deseq2_GSEA.ipynb
```

Run all cells in order to reproduce the analysis and fill `output_data/`.


## Expected Outputs

All outputs are written under `output_data/`.

