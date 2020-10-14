# Public Analysis Models for IFC2CA
This repository contains analysis models implemented within the Ifc-To-Code_Aster ([IFC2CA](https://github.com/IfcOpenShell/IfcOpenShell/tree/v0.6.0/src/ifc2ca)) Project.

---

### File Organization

- `ifcFiles`: In this folder there are all the `ifc` files considered in the examples

- `models`: Each model with all the associated script and result files will be contained in a separate folder within this folder

All model folders contain the following files:

__Input:__
- `{example_name}.json`: json data file of the model
- `{example_name}.med`: mesh file exported from Salome_Meca after executing [`scriptSalome`](https://github.com/IfcOpenShell/IfcOpenShell/blob/v0.6.0/src/ifc2ca/scriptSalome.py)
- `{example_name}.comm`: command file generated from [`scriptCodeAster`](https://github.com/IfcOpenShell/IfcOpenShell/blob/v0.6.0/src/ifc2ca/scriptCodeAstMer.py)

__Output:__
- `{example_name}.mess`: message log file of the interpreted commands in Code_Aster
- `{example_name}.rmed`: result file on the mesh of the structure to visualize in Salome_Meca

---

### Featured Models

### `cantilever_01`
!['geometry and mesh'](models/cantilever_01/geometry&mesh.png)
!['result'](models/cantilever_01/result.png)

### `portal_01`
!['geometry and mesh'](models/portal_01/geometry&mesh.png)
!['result'](models/portal_01/result.png)

### `grid_of_beams`
!['geometry and mesh'](models/grid_of_beams/geometry&mesh.png)
!['result'](models/grid_of_beams/result.png)

### `slab_01`
!['geometry and mesh'](models/slab_01/geometry&mesh.png)
!['result'](models/slab_01/result.png)

### `structure_01`
!['geometry and mesh'](models/structure_01/geometry&mesh.png)
!['result'](models/structure_01/result.png)
