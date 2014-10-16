# BIOMD0000000390: 

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000390.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000390.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000390 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**A quantitative comparison of Calvin–Benson cycle models**   
Anne Arnold, Zoran Nikoloski _Trends in Plant Science_ 2011 Oct 14.
[22001849](http://www.ncbi.nlm.nih.gov/pubmed/22001849) ,  
**Abstract:**   
The Calvin-Benson cycle (CBC) provides the precursors for biomass synthesis
necessary for plant growth. The dynamic behavior and yield of the CBC depend
on the environmental conditions and regulation of the cellular state. Accurate
quantitative models hold the promise of identifying the key determinants of
the tightly regulated CBC function and their effects on the responses in
future climates. We provide an integrative analysis of the largest compendium
of existing models for photosynthetic processes. Based on the proposed
ranking, our framework facilitates the discovery of best-performing models
with regard to metabolomics data and of candidates for metabolic engineering.

**Note:** Model of the Calvin cycle by Giersch et al. (1990, [DOI:10.1007/BF00032595](http://dx.doi.org/10.1007/BF00032595) ). 

The parameter values are taken from Figure 4 and 5. The initial metabolite
values are chosen from the data set of Zhu et al. (2007,
[DOI:10.1104/pp.107.103713](http://dx.doi.org/10.1104/pp.107.103713) ). A
detailed description of all modifications is given in the model described by
Arnold and Nikoloski (2011,
[PMID:22001849](http://www.ncbi.nlm.nih.gov/pubmed/22001849) .

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2012 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


