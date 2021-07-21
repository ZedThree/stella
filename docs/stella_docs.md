---
project: stella
project_github: https://github.com/stellaGK/stella/
summary: stella solves the gyrokinetic equations in general magnetic geometry
author: The stella team
author_description:
    stella has been developed by many developers
    See the [citation
    file](https://github.com/stellaGK/stella/blob/master/CITATION.cff)
    for a complete list
src_dir: ..
exclude_dir: ../externals
             ../tests
             ./html
output_dir: ./html
predocmark: >
docmark: <
fpp_extensions: fpp
                F90
---

stella solves the gyrokinetic-Poisson system of equations in the local limit
using an operator-split, implicit-explicit numerical scheme. It is capable of
evolving electrostatic fluctuations with fully kinetic electrons and an
arbitrary number of ion species in general magnetic geometry, including
stellarators.
