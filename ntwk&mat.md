1. [Equations of Networks](#equations-of-networks)
    1. [The Method of Branch Currents](#the-method-of-branch-currents)
    1. [The Method of Nodal Voltages](#the-method-of-nodal-voltages)
1. [Matrices of Networks](#matrices-of-networks)
    1. [关联矩阵、回路矩阵、割集矩阵](#关联矩阵、回路矩阵、割集矩阵)
1. [References](#references)

## Equations of Networks

A circuit with *b* branches and *n* nodes has *2b* unknowns (branch currents and branch voltages). We have *(n-1)* equations by KCL, *(b-n+1)* by KVL, and *b* from all components/devices (assuming two terminals), thus *2b* equations altogether.

### The Method of Branch Currents
If all branch voltages can be represented by branch currents based on equations of components/devices, the number of unknowns are reduced to *b* (branch currents), and the number of equations are reduced to *b* (*(n-1)* by KCL, and *(b-n+1)* by KVL).

### The Method of Nodal Voltages
Some node is designated as **ground**. The voltages between other nodes and the **ground** are called **nodal voltages**. Branch voltages are the differences between the corresponding nodal voltages. If all branch currents can be represented by branch voltages, and hence nodal voltages, based on equations of components/devices, the number of unknowns are reduced to *n-1* (nodal voltages), and the number of equations are reduced to *n-1*, by KCL.

## Matrices of Networks

### 关联矩阵、回路矩阵、割集矩阵
给一个网络的*n*个结点和*b*条之路编号。据此可以写出一个有*nb*个元素的矩阵**A**。*a<sub>jk</sub> = 1*表示支路*k*的参考方向背离结点*j*，*a<sub>jk</sub> = -1*表示指向，*a<sub>jk</sub> = 0*表示无关联。

![equation](http://latex.codecogs.com/gif.latex?\frac{5+4+(2-3-(6+\frac{4}{5}))}{3(6-2)(2-7)})

## References
