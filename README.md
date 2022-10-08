# SpatialfdaR
FEM codes 
# SpatialfdaR
FEM codes in R 
The codes are basic tools for analyzing spatial data of dimension two using triangular meshes.

They are a subset of the analytical tools in R package fda for analyzing functional data,
where in this case the functions are defined over two dimensional bounded regions that are
covered by a triangular regular mesh.  By "regular" is meant that no vertex of a triangle
is position inside the edge of another triangle.

Three basis functions are associated with each triangle in the mesh.  
The basis function are linear and
create.FEM.basis
eval.FEM.basis
eval.FEM.fd
FEMdensity
insideIndex
makenodes
mass.FEM.R
plotFEM.fd
plotFEM.mesh
randomFEMpts
smooth.FEM.basis
smooth.density.R
squareMesh
stiff.FEM
tricoefCal
triDensity
triquad
