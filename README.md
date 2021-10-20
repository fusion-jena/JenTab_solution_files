# JenTab_solution_files
Results files from JenTab using 3 different modes of execution for CTA

## 2021 [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5584538.svg)](https://doi.org/10.5281/zenodo.5584538)
* JenTab Solutions for SemTab 2021 

## 2020 [![DOI](https://zenodo.org/badge/318490144.svg)](https://zenodo.org/badge/latestdoi/318490144)
* JenTab Solutions for SemTab 2020 using three CTA modes 
  * **P31**
      * selects `instanceOf` or `P31` property for each cell only 
      * **Majority Vote** is used in the selection phase
  * **2 Hops**
      * selects `P31` and its parent via `P279`
      * **LCS** is used in the selection phase
  * **Multi Hops**
      * selects the full tree except the very general classes
      * **LCS** is also used the selection phase
