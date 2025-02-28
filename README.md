## gmsh_elbow_tutorial

**Gmsh .geo file to create a .msh file for the structured elbow tutorial**

P.S.: For OpenFOAM tutorials you must **edit** the file constant/polyMesh/boundary to replace from patch type to wall and empty boundary types:

frontAndBackPlanes
{
        **type            empty;**
        **inGroups        1(empty);**
        nFaces          5590;
        startFace       5446;
}
wall-8
{
        **type            wall;**
        **inGroups        1(wall);**
        nFaces          122;
        startFace       11036;
}
    wall-4
{
        **type            wall;**
        **inGroups        1(wall);**
        nFaces          101;
        startFace       11158;
}    
