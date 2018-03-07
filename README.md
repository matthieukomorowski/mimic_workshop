# MIMIC Critical Care Datathon
## Deep Intelligence to Advance Smart Care – Towards a Learning Health System
## Alhambra Hospital Medical Center – March 2018

### Workshop coordinators: Dr Matthieu Komorowski, Dr Shabbir Syed-Abdul
#### Credit: Material adapted from Drs Tom Pollard and Alistair Johnston, Lab of Computational Physiology at MIT


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

## Installing IPython Notebook

To analyse the data using IPython Notebook, we suggest installing the Anaconda package (Python 3.5) from https://www.continuum.io/downloads. It's a large file, it will take a while to download and install!

## Downloading the materials

If you are familiar with git, please clone this repository. If not, click the 'Download ZIP' button on the right and then unzip the materials onto your computer.

## Installing a SQLite client to read the MIMIC-III demo data

To run SQL queries on the data, you will need a SQLite database manager. Install DB browser: http://sqlitebrowser.org/ 
Once it's installed, select "Open Database" from the main window, then open the data/mimicdata.sqlite file. That's it!

## Analysing the data using IPython Notebook

Once Anaconda is installed, launch 'Juypter Notebook' then open the IPython notebook (.ipynb) file 'mimic_workshop.ipynb' (found in the folder you downloaded earlier).

## Getting access to the full MIMIC-III dataset

If after this workshop you would like to gain access to the full MIMIC-III dataset, which contains rich data for over 40,000 patients, please see: https://mimic.physionet.org/gettingstarted/access/

## Help to improve the workshop

We hope to improve the workshop contents over time and we welcome your contributions. Please raise an issue and/or submit a pull request!

