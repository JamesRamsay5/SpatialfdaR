# SpatialfdaR
FEM codes 
# SpatialfdaR
FEM codes in R 
The codes are basic tools for analyzing spatial data of dimension two using triangular meshes.

They are a subset of the analytical tools in R package fda for analyzing functional data,
where in this case the functions are defined over two dimensional bounded regions that are
covered by a triangular regular mesh.  By "regular" is meant that no vertex of a triangle
is position inside the edge of another triangle.

Each triangle is associated with either three or six basis functions.  

If three, each basis function is piecewise linear and has the value 1 at a vertex.
If six, each basis function is piecewise quadratic and has the value 1 at a vertex or at a midpoint in an edge.

The surface constructed by linear combinations of basis functions is continuous but not differentiable at
nodes or edges.

The functions defined here assume that a mesh has been constructed.  But constructing a mesh can be a
complicated process and automaticaly gernerated meshes often require manual tweaking. For a mesh generating
function please load the package fdapde, or use the delaunay function in the base core if you have a set
of points that you wish to use as nodes of the mesh.
