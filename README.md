# BIOMD0000000149: BIOMD0000000149

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000149.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000149.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000149 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Kim2007 - Crosstalk between Wnt and ERK pathways

Experimental studies have shown that both Wnt and the MAPK pathways are
involved in the pathogenesis of various kinds of cancers (eg. colorectal
cancer). The crosstalk between the two pathways have also been identified.
Here, Kim et al., (2007) have integrated the experimental evidences on
crosstalk mechanisms between the two pathways into a pathway model, and have
identified the existence of a hidden positive feedback loop and suggest that
this positive feedback loop might participate in the pathogenesis of
colorectal cancer.

This model is described in the article:

[A hidden oncogenic positive feedback loop caused by crosstalk between Wnt and
ERK pathways.](http://identifiers.org/pubmed/17237813)

Kim D, Rath O, Kolch W, Cho KH.

Oncogene 2007 Jul; 26(31): 4571-4579

Abstract:

The Wnt and the extracellular signal regulated-kinase (ERK) pathways are both
involved in the pathogenesis of various kinds of cancers. Recently, the
existence of crosstalk between Wnt and ERK pathways was reported. Gathering
all reported results, we have discovered a positive feedback loop embedded in
the crosstalk between the Wnt and ERK pathways. We have developed a plausible
model that represents the role of this hidden positive feedback loop in the
Wnt/ERK pathway crosstalk based on the integration of experimental reports and
employing established basic mathematical models of each pathway. Our analysis
shows that the positive feedback loop can generate bistability in both the Wnt
and ERK signaling pathways, and this prediction was further validated by
experiments. In particular, using the commonly accepted assumption that
mutations in signaling proteins contribute to cancerogenesis, we have found
two conditions through which mutations could evoke an irreversible response
leading to a sustained activation of both pathways. One condition is enhanced
production of beta-catenin, the other is a reduction of the velocity of MAP
kinase phosphatase(s). This enables that high activities of Wnt and ERK
pathways are maintained even without a persistent extracellular signal. Thus,
our study adds a novel aspect to the molecular mechanisms of carcinogenesis by
showing that mutational changes in individual proteins can cause fundamental
functional changes well beyond the pathway they function in by a positive
feedback loop embedded in crosstalk. Thus, crosstalk between signaling
pathways provides a vehicle through which mutations of individual components
can affect properties of the system at a larger scale.

Figure 6 of the reference publication has been reproduced. The model as such
reproduces the plots corresponding to the normal conditions. To obtain
simulations under 1) beta-cataenin mutation; set V12=0.846 (two-fold of the
beta-catenin synthetic rate than the normal system. i.e. 2*0.426), 2) PP2A
mutation; set Vmax4=Vmax5=33.75 (three-fourths of the PP2A activity that the
normal system. i.e. (3/4)*45). The simulation was performed using Copasi 4.10
(Build 55).

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000149](http://identifiers.org/biomodels.db/BIOMD0000000149) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


