# Columnar Analysis in High Energy Physics
Welcome to the ColumnarHEP! This repository contains Jupyter Notebooks and Presentations related to Columnar Analysis using data from two folders: 2022-08-01-uproot-awkward-columnar-hats/data and data. The notebooks showcase the use of tools like Uproot, Awkward Array, Coffea , etc. and draws insight from the provided datasets. Below, you'll find an overview of the repository contents and instructions on how to use the materials.

## Table of Contents

- [Introduction](#introduction)
- [Repository Contents](#repository-contents)
- [Requirements](#requirements)
- [Usage](#usage)
- [Presentation](#presentation)
- [References and More Resources](#References-and-More-Resources)
- [License](#license)

## Introduction

This repo is a documentation of my work at CMSLab, School of Physics at the University of Hyderabad. My main focus is to perform data analysis of CMS, CERN data using COFFEA framework. In this repository, you will find the presentations that I made to understand tools like Uproot, Awkward array, COFFEA , dask etc. 

## Repository Contents

Description of the contents :

- **Notebooks:** This folder contains the Jupyter Notebooks used for data analysis. Provide a brief description of each notebook, its objectives, and how it utilizes the data from the two folders.
  - `speedtest.ipynb`: This compares the compilation time for different idioms and libraries relevant for analysis.
  - `UprootAndAwkward.ipynb`: This is the main jupyter notebook associated with ColumnarI.pptx. This file contains my notes on Uproot and Awkward Array. For this I have followed the [Uproot and Awkward array FNAL HATS](https://indico.cern.ch/event/1186603//) .
  - `Coffea.ipynb`: This is the main jupyter notebook associated with ColumnarII.pptx (Upcoming; Not yet finished!). This file contains my notes on Uproot and Awkward Array. For this I have followed the [Coffea FNAL HATS](https://indico.cern.ch/event/1297678/) .
  - `SimpleAnalysisExplained.ipynb`: A simple analysis to get a Z boson peak with single Electron dataset. This utilises the knowledge of uproot and awkward array only. Try this after going through UprootAndAwkward.ipynb .

- **Data:** This folder contains the datasets used in the notebooks. Explain the purpose of each dataset and any data preprocessing steps you've taken.

- **Presentations:** This folder contains the Presentation explaining the general concepts of data analysis used in this project. Provide a brief overview of the topics covered in the presentation.

## Requirements

Softwares and libraries required to run the Jupyter Notebooks and additional dependencies :

- Python 3.8 or higher
- Jupyter Notebook or Jupyter Lab
- pandas
- numpy
- matplotlib
- ROOT
- uproot
- awkward array
- numba
- vector
- hist
- IPython
- Coffea
- Particle
- Rich


## Usage

1. Clone the repository to your local machine using `git clone https://github.com/prayagyadav/ColumnarHEP.git`.
2. Navigate to the repository directory: `cd ColumnarHEP`.
3. Open Jupyter Notebook using the command `jupyter-lab`.
5. Run the notebooks from the Jupyter-lab interface.

NOTE: Download the ZZTO4e.root dataset in the Data folder by following the instructions given in the Download.md .

## Presentation

- ColumnarI.pptx explains about the need fro libraries like Uproot and Awkward Array. It assumes basic knowledge of ROOT and Python.
- ColumnarII.pptx(Not yet uploaded!) discusses the need for columnar analysis and explains the key features of Coffea.

## References and More Resources

I have followed the following LPC HATS while learning about Columnar Analysis. <br/>
[Uproot and Awkward array link](https://indico.cern.ch/event/1186603//) <br/>
[Coffea link](https://indico.cern.ch/event/1297678/) <br/>

## License

This repository is licensed under the MIT license. For more information, see the LICENCE.md file.

---
