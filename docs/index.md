# Finite Element Analysis with OpenSees

This git repository contains documentation and tutorial examples for conducting finite element 
analysis through the [OpenSees simulation platform](https://github.com/OpenSees/OpenSees). 

## Material documentation

The documentation concerns the newly developed materials in OpenSees. 

### Axial curves

The documentation related to the axial non-linear load-transfer functions ($t-z$ and $Q-z$ curves). 
The curves are included as [uniaxial materials](https://opensees.github.io/OpenSeesDocumentation/user/manual/material/uniaxialMaterial.html), which provide a uniaxial force-deformation relationships.

**Unified CPT-based method**

- [Shaft load-transfer function SANDS](materials/axial/TzSandCPT.md)
- [End bearing load-transfer function sands](materials/axial/QbSandCPT.md)

## Worked examples

Worked examples using [OpenSeesPy](https://github.com/zhuminjie/OpenSeesPy), the Python interpreter 
of OpenSees, are provided through jupyter notebooks.

!!! note

    The developped materials might have not been included yet in any oficial OpenSees release. In the 
    meanwhile, interested users may use the materials by importing the provided DLL file 
    ```opensees.pyd``` as shown in the notebooks. 

!!! warning

    The DLL can only be run in an environment with **Python 3.8**.

!!! info

    The DDL can be [downloaded from here](examples/opensees.pyd)

!!! tip

    If import errors are experienced when importing the DLL through the notebook, try to install
    OpenSeesPy in the current virtual environment ```pip install openseespy```. 

### Axial pile response

The provided material for the worked cases focusing on piles under axial loading is listed below.

**Unified CPT-based method in SANDS**

- The [tutorial notebook](examples/1_EuripidesB2.ipynb)
- Excel spreadsheet with assumed soil inputs can be [downloaded from here](examples/inputs/TableB2.xlsx)