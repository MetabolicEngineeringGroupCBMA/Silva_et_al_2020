# Silva et al. 2020
This repository contains Jupyter notebooks describing cloning using
[Python](https://www.python.org),
[Jupyter notebooks](https://jupyter.org) and
[pydna](https://github.com/BjornFJohansson/pydna).

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

The notebooks and other files in this repository accompany the publication:

![button](references/abstract.png)

**Ioannidis, J. P. A. (2016). Why Most Clinical Research Is Not Useful. PLoS Medicine, 13(6), e1002049.**
[PubMed](https://pubmed.ncbi.nlm.nih.gov/27328301)
[website](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1002049)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)


The notebooks can be visualized in a number of ways.
Each notebook (.ipynb) is accompanied by a HTML file with the same name but with an (.html)
extension. These can be opened in a web browser without installing any software.

The notebooks (.ipynb) can be opened in the browser through the nbviewer service
[here](http://nbviewer.jupyter.org/github/MetabolicEngineeringGroupCBMA/Silva_et_al_2020/blob/master/notebooks/index.ipynb)
or directly in Github [here](notebooks/index.ipynb).

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)

## Significant files

[pYPK7_TEF1_RPS7B](notebooks/pYPK7_TEF1_RPS7B.ipynb) Yeast expression vector with TEF1 promoter and KanMX4 marker.
This vector was used as a source for the promoter and terminator for the pLBL2 and pLBL3 plasmids.


[pLBL2](notebooks/pLBL2.ipynb) Yeast expression vector with TEF1 promoter, RPS7B terminator and a URA3 marker.


[pLBL3](notebooks/pLBL3.ipynb) Same as pLBL2 but with the URA3 marker replaced by a LEU2 marker.


[pLBL3_PiXI_opt](notebooks/pLBL3_PiXI_opt.ipynb)


[pLBL3_XI](notebooks/pLBL3_XI.ipynb)


[pYPK0_XTTRRG](notebooks/pYPK0_XTTRRG.ipynb)

The index.ipynb notebook is the place to start as it has links to the other notebooks.

Each notebook contain links (usually in the end) to the resulting sequences in Genbank flat file format.

These notebooks are tested on the github action build service.

This means that the notebook outputs are re-executed and compared with saved
results once per week to ensure [reproducibility](https://en.wikipedia.org/wiki/Replication_crisis).

If the badge below is green, all tests gave the expected results.

[![test jupiter notebooks](https://github.com/MetabolicEngineeringGroupCBMA/Silva_et_al_2020/workflows/test%20jupiter%20notebooks/badge.svg)](
https://github.com/MetabolicEngineeringGroupCBMA/Silva_et_al_2020/actions?query=workflow%3A%22test+jupiter+notebooks%22
)

For each Jupyter notebook file, there is a html version with the same name but with a
 `.html` extension instead of `.ipynb`. These files are static and can be viewed with any
modern web browser.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)
