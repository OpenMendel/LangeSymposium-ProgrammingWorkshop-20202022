# OpenMendel Workshop @ Lange Symposium

This repo contains the OpenMendel tutorials presented in the programming workshop at the inaugural Lange's Symposium on Feb 21-22, 2020.

## Presenters

* Ben Chu, doctoral student, Computational Medicine (Biomathematics), UCLA  
* Chris German, doctoral student, Biostatistics, UCLA  
* Sarah Ji, doctoral student, Biostatistics, UCLA  
* Juhyun Kim, doctoral student, Biostatistics, UCLA  
* Hua Zhou, Associate Professor, Biostatistics, UCLA  

## Syllabus

| Time | Topic | Presenter |  
|:-----------|:------------|:------------|  
| 8:30-8:50 | Import genotype data by SnpArrays.jl \[[ipynb](./01-snparrays/SnpArraysTutorial.ipynb)\] \[[html](https://openmendel.github.io/LangeSymposium-ProgrammingWorkshop-20202022/01-snparrays/SnpArraysTutorial.html)\] and VCFTools.jl | Hua Zhou |  
| 8:50-9:10 | Variance component models | Juhyun Kim |  
| 9:10-9:30 | Haplotyping and imputation by MendelImpute.jl \[[ipynb](./04-impute/MendelImpute_Tutorial.ipynb)\]| Ben Chu |  
| 9:30-9:50 | GWAS by IHT \[[ipynb](./05-gwas/MendelIHT_tutorial.ipynb)\] | Ben Chu |  
| 9:50-10:10 | GWAS for ordinal trait | Chris German |  
| 10:10-10:30 | Trait simulation | Sarah Ji |  

## Binder

To try the Jupyter notebook in cloud, click the Binder icon below:  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OpenMendel/LangeSymposium-ProgrammingWorkshop-20202022.git/master)

## Run Jupyter notebooks on your own laptop

This is **not** recommended during this workshop, since your software environment (OS, Julia version, package versions, etc.) may be quite different from that assumed by the Jupyter notebooks. In case you want to run Jupyter notebooks on your own machine, simply `git clone https://github.com/OpenMendel/LangeSymposium-ProgrammingWorkshop-20202022.git` to sync the most recent course materials to your computer and install all needed Julia packages.

