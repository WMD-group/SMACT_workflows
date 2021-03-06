[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# SMACT Workflows
A series of computational experiments using the open-source package [SMACT](https://github.com/WMD-group/smact).

## Python
An introduction to the importance of Python for scientists, and the basics of the coding language, is available [elsewhere](https://www.researchgate.net/profile/Brian_Toby/publication/269995603_Whypython_scientists_should_learn_to_program_in_Python/links/549dbd610cf2b803713a7bec.pdf). For a complete beginner, [Codecademy](https://www.codecademy.com/learn/learn-python-3) or [Datacamp](https://www.datacamp.com/courses/intro-to-python-for-data-science) are good places to start. 

## Requirements
The workflows are presented in [Jupyter notebooks](http://jupyter.org). Jupyter is included with standard Python distributions such as [Anaconda](https://www.continuum.io/downloads) and the [Homebrew Superpack for Mac](http://stronginference.com/ScipySuperpack/). There are dependencies on [SMACT](https://github.com/WMD-group/smact) and for some practicals [ASE](https://wiki.fysik.dtu.dk/ase/) and [Pymatgen](www.pymatgen.org).

## Background
There is a strong demand for functional materials across a wide range of technologies. The motivation can include cost reduction, performance enhancement, or to enable a new application. Data collections such as the [Materials Project](https://www.materialsproject.org), [NREL Materials Database](http://materials.nrel.gov) and the [Open Quantum Materials Database](http://oqmd.org) are valuable resources, but they cover the properties of *known* compounds as calculated using high-level quantum mechanical theories.

We have been developing low-cost procedures for screening hypothetical materials in the [SMACT](https://github.com/WMD-group/SMACT) package. These workflows show how this framework can be used for simple calculations on your own computer. 

## Workflows

### [Outreach](./outreach_2020) [![badge](https://img.shields.io/badge/launch%20-tutorial-579ACA.svg)](https://mybinder.org/v2/gh/WMD-group/SMACT_workflows/master?filepath=outreach_2020%2Fpython3_intro_2020.ipynb)[![badge](https://img.shields.io/badge/launch%20-notebook-579ACA.svg)](https://mybinder.org/v2/gh/WMD-group/SMACT_workflows/master?filepath=outreach_2020%2Fmaterials_combinations_2020.ipynb)

A steamlined version of the element combinations practical. It is a one hour activity for school students.

### [Masters practical](./masters_practical)
This is a two-part practical that has been used as a teaching aid for masters courses in the UK (University of Bath) and Korea (Yonsei University). It is probably the most pedagogical example and is a good place to start. It consists of two parts:

- *Elemental Combinations* `jupyter notebook Combinations_practical.ipynb`. The "bread and butter" of SMACT. This covers the basics of how the search space for new inorganic materials can be constructed by considering raw combinations of elements. The resulting space is then filtered using rules based on simple chemical ideas such as electronegativity and charge neutrality. 
- *Solar Cell Contacts* `jupyter notebook ELS_practical.ipynb` covers an example procedure for matching the surfaces of two inorganic materials together, as described in [this publication](https://pubs.rsc.org/en/content/articlelanding/2016/tc/c5tc04091d#!divAbstract) by Butler et. al.

### [Solar oxides](./Solar_oxides)
A simple workflow for generating quaternary oxide compositions and  a featurised dataframe for machine learning. A more extensive example can be found [elsewhere](https://github.com/WMD-group/Solar_oxides_data).
