# SMACT Workflows
A series of computational experiments using the open-source package [SMACT](https://github.com/WMD-group/smact).

## Python
An introduction to the importance of Python for scientists, and the basics of the coding language, is available [elsewhere](https://www.researchgate.net/profile/Brian_Toby/publication/269995603_Why_scientists_should_learn_to_program_in_Python/links/549dbd610cf2b803713a7bec.pdf). For a complete beginner, [Codecademy](https://www.codecademy.com/learn/python) is a good place to start. 

## Requirements
The practicals are written in [Jupyter notebooks](http://jupyter.org). Jupyter is included with standard Python distributions such as [Anaconda](https://www.continuum.io/downloads) and the [Homebrew Superpack for Mac](http://stronginference.com/ScipySuperpack/). There are dependencies on [SMACT](https://github.com/WMD-group/smact) and for some practicals [ASE](https://wiki.fysik.dtu.dk/ase/).

## Background
There is a strong demand for new functional materials across a wide range of technologies. The motivation can include cost reduction, performance enhancement, or to enable a new application. 

The problem is that the number of *possible* materials is infinite, when multi-component systems are considered. The challenge for materials scientists is to navigate the phase space as efficiently as possible. We have collected an extended reading list around this topic on [Mendeley](https://www.mendeley.com/groups/8113991/materials-design/overview/). 

Data collections such as the [Materials Project](https://www.materialsproject.org), [NREL Materials Database](http://materials.nrel.gov) and the [Open Quantum Materials Database](http://oqmd.org) are valuable resources, but they cover the properties of *known* compounds as calculated using high-level quantum mechanical theories.

We have been developing a low-cost procedure for screening hypothetical materials in the [SMACT](https://github.com/WMD-group/SMACT) package. These tutorials show how this framework can be used for simple calculations on your own computer. 

## Workflows
### Masters practical
This directory contains a two-part practical that has been used as a teaching aid for masters courses in the UK (University of Bath) and Korea (Yonsei University).
It consists of two parts.

- *Elemental Combinations* `Jupyter notebook Combinations_practical.ipynb` covers the basics of how the search space for new inorganic materials can be constructed by taking raw combinations of elements. The resulting space is then filtered using simple chemical ideas such as electronegativity and charge neutrality. 
- *Solar Cell Contacts* `Jupyter Notebook ELS_practical.ipynb` covers an example procedure for matching the surfaces of two inorganic materials together, as described in [this publication](https://pubs.rsc.org/en/content/articlelanding/2016/tc/c5tc04091d#!divAbstract) by Butler et. al.

## Public Server
It can be useful to run the notebook on a single machine, where others can log in via a web browswer. This process is detailed [elsewhere](http://jupyter-notebook.readthedocs.org/en/latest/public_server.html).


