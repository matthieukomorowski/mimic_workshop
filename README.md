# MIMIC Critical Care Datathon

These are training materials for the MIMIC Critical Care Database. The package includes:

- a demo version of SQLite MIMIC which requires no installation.
- some sample SQL queries which can be used to query the MIMIC data
- an IPython Notebook which connects to the demo MIMIC database and allows analysis to be carried out using Python.

## What is MIMIC-III?

MIMIC-III is a widely-used, freely available dataset developed by the MIT Lab for Computational Physiology, comprising deidentified health data associated with >40,000 critical care patients. It includes demographics, vital signs, laboratory tests, medications, and more. Details are available on the MIMIC website: https://mimic.physionet.org/

## Workshop overview 

During the workshop, you will:

- Learn about MIMIC-III, the publicly accessible critical care database 
- Create a local version of MIMIC-III with a small sample of patients
- Explore the patient data using SQL
- Plot and analyse the data using Python
- Get inspiration for future research projects

## Downloading the materials

If you are familiar with git, please clone this repository. If not, click the 'Download ZIP' button on the right and then unzip the materials onto your computer.

## Installing a SQLite client to read the MIMIC-III demo data

To run SQL queries on the data, you will need a SQLite database manager. Install DB browser: http://sqlitebrowser.org/ 
Once it's installed, select "Open Database" from the main window, then open the data/mimicdata.sqlite file. That's it!

## Analysing the data using IPython Notebook

To analyse the data using IPython Notebook, we suggest installing the Anaconda package from https://www.continuum.io/downloads. 

Once IPython is installed, run ```ipython notebook``` from the command line to open IPython Notebook, then open one of the notebook (.ipynb) files (for example, 01-example-patient-heart-failure.ipynb).

## Getting access to the full MIMIC-III dataset

If after this workshop you would like to gain access to the full MIMIC-III dataset, which contains rich data for over 40,000 patients, please see: https://mimic.physionet.org/gettingstarted/access/

## Help to improve the workshop

We hope to improve the workshop contents over time and we welcome your contributions. Please raise an issue and/or submit a pull request!





