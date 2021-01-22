# QIIME2 artifactAPI TUTORIALS
> These tutorials are an adaptation of the same tutorials that can be found on the official QIIME 2 docs website. The original tutorials uses the QIIME 2 CLI interface.


## Table of contents

1. Setup
2. Fecal microbiota transplantation tutorial
3. Atacama soil microbiome tutorial
4. Parkinson’s Mouse Tutorial
5. Instructions
6. Questions


## 1. Setup

This guide assumes you have QIIME 2 installed (e.g. using [this procedure](https://docs.qiime2.org/2020.8/install/native/)). To execute the script properly, open this notebook in a Jupyter Notebook from within a conda QIIME 2 environment.


## 2. Fecal Microbiota Transplantation Tutorial

This repository includes Jupyter notebooks to generate the figures using the 2020.2 version of QIIME 2. 

### Notes to the reader
The data used in this tutorial is derived from a Fecal Microbiome Transplant study. This tutorial dataset is a subsample of the data generated for this study. While we do not provide all the data in this repository we provide the Metadata tables, which contains all of the clinical data.

### Repository Structure

* Artifact API
This directory contains codes for each step of analysis. More descriptions can be found within the [webiste](https://docs.qiime2.org/2020.8/).

* Data
This directory contains the input data download URL, including Metadata and subsample data. You can choose either a 1% subsample of the reads or a 10% subsample of the reads.


## 3. Atacama Deseret Microbiome Tutuorial


### Notes to the reader

In this tutorial you will use QIIME 2 to perform an analysis of soil samples from the Atacama Desert in northern Chile. This tutorial utilizes the data generated for this study and metadata tables.

### Repository Structure

* Artifact API
This directory contains codes for each step of analysis. he sequences for the full study are accessible at EBI with accession [PRJEB17694](https://www.ebi.ac.uk/ena/browser/view/PRJEB17694); processed tables from the full study can be downloaded from the [Qiita](https://qiita.ucsd.edu/) database from study 10483.data
This directory contains the input data download URL, including metadata table and multiplexed reads.

* Data
This directory contains the input data download URL, including metadata table and multiplexed reads.questions


## 4. Parkinson’s Mouse Tutorial

This repository includes the Jupyter notebooks to generate the figures using the 2020.2 version of QIIME 2. The full study is accessible at [Sampson et al, 2016](https://pubmed.ncbi.nlm.nih.gov/27912057/)


### Notes to the reader
This tutorial demonstrates a “typical” QIIME 2 analysis of 16S rRNA.  This tutorial dataset is a subset of data from two human donors. While we do not provide all the data in this repository we provide the Metadata tables, which contains all of the clinical data.

### Repository Structure

* Artifact API
This directory contains codes for each step of analysis. More descriptions can be found within the [website](https://docs.qiime2.org/2020.8/).

* Data
This directory contains the input data download URL, including metadata and subsample data. 


## 5. Instructions
These notebooks contain step-by-step instructions, which provide explanatory information for every part of analysis.

## 6. Questions
The crucial figures and tables from the paper which can be interpreted are followed with clarifying questions to ensure understanding and obtain essential information of tutorials. 

