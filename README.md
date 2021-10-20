# JenTab_solution_files
Results files from JenTab using 3 different modes of execution for CTA

## Modes
  * **P31**
      * selects `instanceOf` or `P31` property for each cell only 
      * **Majority Vote** is used in the selection phase
  * **2 Hops**
      * selects `P31` and its parent via `P279`
      * **LCS** is used in the selection phase
  * **Multi Hops**
      * selects the full tree except the very general classes
      * **LCS** is also used the selection phase
