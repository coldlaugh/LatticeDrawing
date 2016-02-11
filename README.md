# LatticeDrawing
LatticeDrawing is a Matlab and python package for plotting lattices. 

* **Easy to use:** The only input for LatticeDrawing is the unit cell and primitive vectors. LatticeDrawing will finish the rest of the work for you.
* **Fully customizable** If you are not satisfied with the default settings of LatticeDrawing, you can customize almost every aspect of it.

# Examples

```matlab
%Drawing a 2D square lattice in matlab
UnitCell=[0];
PrimVector=[1 0; 0 1];
LatticeDrawing(UnitCell,PrimVector)
```

```python
#Drawing a 2D square lattice in python
import numpy as np
import LatticeDrawing
UnitCell=np.array([0])
PrimVector=np.matrix([[1,0],[0 1]])
LatticeDrawing.plot(UnitCell,PrimVector)
```
