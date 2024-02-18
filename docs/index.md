# Finite Element Analysis with OpenSees

This git repository contains documentation and tutorial examples for conducting finite element analysis through the [OpenSees simulation platform](https://github.com/OpenSees/OpenSees). 

## Material documentation

The documentation concerns the newly developed materials in OpenSees. 

#### Axial curves

The documentation related to the axial non-linear load-transfer functions (t-z and Q-z curves). The curves are included as [uniaxial materials](https://opensees.github.io/OpenSeesDocumentation/user/manual/material/uniaxialMaterial.html), which provide a uniaxial force-deformation relationships.

**Unified CPT-based method**

- [Shaft load-transfer function SANDS](materials/axial/TzSandCPT.md)
- [End bearing load-transfer function sands](materials/axial/QbSandCPT.md)


## Worked examples

Worked examples using [OpenSeesPy](https://github.com/zhuminjie/OpenSeesPy), the Python interpreter of OpenSees, are provided. The tutorials showcase application cases of the developed materials.


