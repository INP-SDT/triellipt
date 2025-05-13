
# <img src="./docs/configs/logo.png" width="30" height="30"> triellipt

An adaptive finite-element solver for elliptic PDEs.

## Features

**Meshes:**
- Has an interface to read GMSH meshes  
- Supports [*conforming*](#conforming-mesh) and [*non-conforming*](#non-conforming-mesh) triangle meshes
- Provides a flexible framework for mesh [*adaptation*](#adaptive-mesh)

**Discretization:**

*Features*

- Operates on linear elements and macroelements¹
- Ensures mass conservation on adaptive meshes

¹ Under development

*Methods*

- Nodal Continuous Galerkin Method 
- Nodal Finite Volume Method
- Edge-based HPS¹ discretization

¹ Hierarchical Poincaré–Steklov

## Funding

**Funded by the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation) —
project number [515939493](https://gepris.dfg.de/gepris/projekt/515939493?language=en)**

## Status

- Undergoing usability testing.
- Work on the user guide is in progress.

## Documentation

- ✅ Check the live documentation [here](https://igsemenov.github.io/triellipt/).
- 📄 Check the local source documentation [here](docs/sources/index.md).
- 💾 Offline HTML documentation is available by opening `docs/index.html`.

## Triangle meshes

### Conforming mesh

<img src="./docs/images/conforming-mesh.png" width="450">

### Non-conforming mesh

<img src="./docs/images/non-conforming-mesh.png" width="450">

### Adaptive mesh

&nbsp;&nbsp;&nbsp;&nbsp;<img src="docs/images/circ-amr.gif" alt="Demo GIF" width="400"/>

