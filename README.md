# MODEL1302010002: MODEL1302010002

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1302010002.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1302010002.git@20140916`

## Usage

Importing the model package.

`import MODEL1302010002 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Pitkanen2014 - Metabolic reconstruction of Chaetomium globosum using CoReCo

This model was reconstructed with the CoReCo method (Comparative
ReConstruction of genome-scale metabolic networks) from protein sequence and
phylogeny data.

This model is described in the article:

[Comparative Genome-Scale Reconstruction of Gapless Metabolic Networks for
Present and Ancestral
Species](http://identifiers.org/doi/10.1371/journal.pcbi.1003465)

Esa Pitkänen, Paula Jouhten, Jian Hou, Muhammad Fahad Syed, Peter Blomberg,
Jana Kludas, Merja Oja, Liisa Holm, Merja Penttilä, Juho Rousu, Mikko Arvas

PLoS Comput Biol. 2014 Feb 6;10(2):e1003465

Abstract:

We introduce a novel computational approach, CoReCo, for comparative metabolic
reconstruction and provide genome-scale metabolic network models for 49
important fungal species. Leveraging on the exponential growth in sequenced
genome availability, our method reconstructs genome-scale gapless metabolic
networks simultaneously for a large number of species by integrating sequence
data in a probabilistic framework. High reconstruction accuracy is
demonstrated by comparisons to the well-curated Saccharomyces cerevisiae
consensus model and large-scale knock-out experiments. Our comparative
approach is particularly useful in scenarios where the quality of available
sequence data is lacking, and when reconstructing evolutionary distant
species. Moreover, the reconstructed networks are fully carbon mapped,
allowing their use in 13C flux analysis. We demonstrate the functionality and
usability of the reconstructed fungal models with computational steady-state
biomass production experiment, as these fungi include some of the most
important production organisms in industrial biotechnology. In contrast to
many existing reconstruction techniques, only minimal manual effort is
required before the reconstructed models are usable in flux balance
experiments. CoReCo is available at http://esaskar.github.io/CoReCo/.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1302010002](http://identifiers.org/biomodels.db/MODEL1302010002) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


