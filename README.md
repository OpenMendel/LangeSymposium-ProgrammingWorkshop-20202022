# OpenMendel Workshop @ Lange Symposium

This repo contains the OpenMendel tutorials presented in the programming workshop at the inaugural Lange's Symposium on Feb 21-22, 2020.

## Presenters

* Ben Chu, doctoral student, Computational Medicine (Biomathematics), UCLA  
* Chris German, doctoral student, Biostatistics, UCLA  
* Sarah Ji, doctoral student, Biostatistics, UCLA  
* Juhyun Kim, doctoral student, Biostatistics, UCLA  
* Hua Zhou, Associate Professor, Biostatistics, UCLA  

## How to run tutorials?

To try the Jupyter notebooks in cloud, click the Binder icon below:  
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OpenMendel/LangeSymposium-ProgrammingWorkshop-20202022/master)

## What is OpenMendel

- **Mendel**: comprehensive genetic analysis software by Ken Lange, Eric Sobel, Janet Sinsheimer, and  generations of students.   

- **Julia**: _Walk Like Python; Run Like C._

- Ken's vision: **Julia + Mendel = OpenMendel**.

## How to contribute?

- Browse existing OpenMendel packages: <https://github.com/OpenMendel>. Don't forget to star them 😄

- Ask questions, file bug reports, and request new features by GitHub **Issues**.  

- Get credit for you code contribution via GitHub **Fork** and **Pull Requests**. 

- Want project ideas? Talk to any of us or come to OpenMendel meetings (every Wed in winter quarter).  

    - BGEN.jl   

    - enhancement to variance component models packages  

    - and many more  

## Syllabus

| Time | Topic | Presenter |  
|:-----------|:------------|:------------|  
| 8:30-8:50 | Import genotype data by SnpArrays.jl \[[ipynb](./01-snparrays/SnpArraysTutorial.ipynb)\] \[[html](https://openmendel.github.io/LangeSymposium-ProgrammingWorkshop-20202022/01-snparrays/SnpArraysTutorial.html)\] and VCFTools.jl \[[ipynb](./02-vcftools/vcftools.ipynb)\] \[[html](https://openmendel.github.io/LangeSymposium-ProgrammingWorkshop-20202022/02-vcftools/vcftools.html)\] | Hua Zhou |  
| 8:50-9:10 | Variance component models \[[ipynb](./03-varcomp/VarianceComponentModels.ipynb)\] \[[html](https://openmendel.github.io/LangeSymposium-ProgrammingWorkshop-20202022/03-varcomp/VarianceComponentModels.html)\] | Juhyun Kim |  
| 9:10-9:30 | GWAS by IHT \[[ipynb](./05-iht/MendelIHT_tutorial.ipynb)\]\[[html](https://openmendel.github.io/LangeSymposium-ProgrammingWorkshop-20202022/05-iht/MendelIHT_tutorial.html)\] | Ben Chu |  
| 9:30-09:50 | GWAS for ordinal trait \[[ipynb](./06-ordinal/ordinalgwas.ipynb)\] \[[html](https://openmendel.github.io/LangeSymposium-ProgrammingWorkshop-20202022/06-ordinal/ordinalgwas.html)\]| Chris German |  
| 09:50-10:10 | Trait simulation \[[ipynb](./07-traitsim/TraitSimulation.ipynb)\] \[[html](https://openmendel.github.io/LangeSymposium-ProgrammingWorkshop-20202022/07-traitsim/TraitSimulation.html)\] | Sarah Ji |  
| 10:10-10:30 | Extra time |  |  

## Wifi

Use `Eduroam` or `UCLA_WEB`. 

- `UCLA_WEB` does not need password.  
- `Eduroam` needs authentication by your institute. For example, UCLA affiliates can log in `Eduroam` by `[joebruin]@ucla.edu`  and the UCLA password. 

## Run Jupyter notebooks on your own laptop

This is **not** recommended during this workshop, since your software environment (OS, Julia version, package versions, etc.) may be quite different from that assumed by the Jupyter notebooks. In case you want to run Jupyter notebooks on your own machine, simply `git clone https://github.com/OpenMendel/LangeSymposium-ProgrammingWorkshop-20202022.git` to sync the most recent course materials to your computer and install all needed Julia packages.
