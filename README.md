# Data Wrangling Repository

## Project Objective
The purpose of this repository is to unify three most popular databases with peptide-HLA-TCR sequences which can be used in immunologic projects.

## Biological background
*T-Cells* are one of the important white blood cells which take a huge role in a immune response. *T-Cell Receptor* (**TCR**) is a protein complex found on the surface of T-Cells which recognizes the cells that are foreign or pathologic in a human body (eg. viruses or cancer cells). To be clear, T-Cells recognize not the cells in a whole but the peptides which are presented on the cell's surface by *Human Leucocyte Antigen* (**HLA**).  The main role of HLA is to present these peptides to T-Cells.
In summary - the cell presents a **peptide** using HLA and T-Cell can (or cannot) recognize it by using T-Cell Receptor.
![peptide-HLA-TCR](/img/pHLATCR.png/)

## Datasets
Datasets used in this notebook are three most popular databases with TCR sequences. These databases are:
 - [McPAS-TCR](http://friedmanlab.weizmann.ac.il/McPAS-TCR/)
 - [TBAdb](https://db.cngb.org/pird/tbadb/)
 - [VDJdb](https://vdjdb.cdr3.net)

## Technology 
Code is written using Python language and Jupyter Notebook.
Libraries used in this notebook include:
 - pandas
 - os
 - json
