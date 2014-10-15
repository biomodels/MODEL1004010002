# MODEL1004010002: kuwahara2010

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1004010002.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1004010002.git@20140916`


# Model Notes


This the detailed model for 42°C from the article:  
**Temperature Control of Fimbriation Circuit Switch in Uropathogenic _Escherichia coli_ : Quantitative Analysis via Automated Model Abstraction. **   
Hiroyuki Kuwahara, Chris J. Myers and Michael S. Samoilov _PLoS Comput Biol._
2010 6(3): e1000723. doi:
[10.1371/journal.pcbi.1000723](http://dx.doi.org/10.1371/journal.pcbi.1000723)
,  
**Abstract:**   
Uropathogenic Escherichia coli (UPEC) represent the predominant cause of
urinary tract infections (UTIs). A key UPEC molecular virulence mechanism is
type 1 fimbriae, whose expression is controlled by the orientation of an
invertible chromosomal DNA element—the fim switch. Temperature has been shown
to act as a major regulator of fim switching behavior and is overall an
important indicator as well as functional feature of many urologic diseases,
including UPEC host-pathogen interaction dynamics. Given this panoptic
physiological role of temperature during UTI progression and notable empirical
challenges to its direct in vivo studies, in silico modeling of corresponding
biochemical and biophysical mechanisms essential to UPEC pathogenicity may
significantly aid our understanding of the underlying disease processes.
However, rigorous computational analysis of biological systems, such as fim
switch temperature control circuit, has hereto presented a notoriously
demanding problem due to both the substantial complexity of the gene
regulatory networks involved as well as their often characteristically
discrete and stochastic dynamics. To address these issues, we have developed
an approach that enables automated multiscale abstraction of biological system
descriptions based on reaction kinetics. Implemented as a computational tool,
this method has allowed us to efficiently analyze the modular organization and
behavior of the E. coli fimbriation switch circuit at different temperature
settings, thus facilitating new insights into this mode of UPEC molecular
virulence regulation. In particular, our results suggest that, with respect to
its role in shutting down fimbriae expression, the primary function of FimB
recombinase may be to effect a controlled down-regulation (rather than
increase) of the ON-to-OFF fim switching rate via temperature-dependent
suppression of competing dynamics mediated by recombinase FimE. Our
computational analysis further implies that this down-regulation mechanism
could be particularly significant inside the host environment, thus
potentially contributing further understanding toward the development of novel
therapeutic approaches to UPEC-caused UTIs.

This model is parametrized for 42°C. Some parameters and initial conditions
are temperature dependent and have to be changed to simulate other conditions
as listed in table 4 (doi: [10.1371/journal.pcbi.1000723.t004](http://dx.doi.o
rg/10.1371/journal.pcbi.1000723.t004) ), table 5(doi: [10.1371/journal.pcbi.10
00723.t005](http://dx.doi.org/10.1371/journal.pcbi.1000723.t005) ) and 6(doi: 
[10.1371/journal.pcbi.1000723.t006](http://dx.doi.org/10.1371/journal.pcbi.100
0723.t006) ) and supplement S1 (doi: [10.1371/journal.pcbi.1000723.s001](http:
//dx.doi.org/10.1371/journal.pcbi.1000723.t004) ) of the publication.  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


