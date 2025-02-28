## gmsh_elbow_tutorial

**Gmsh .geo file to create a .msh file for the structured elbow tutorial**

P.S.: For OpenFOAM tutorials you must **edit** the file *constant/polyMesh/boundary* to replace these *patch* types to *wall* and *empty* boundary types:

frontAndBackPlanes  
{  
&nbsp;&nbsp;&nbsp;&nbsp;**type            empty;**    
&nbsp;&nbsp;&nbsp;&nbsp;**inGroups        1(empty);**  
&nbsp;&nbsp;&nbsp;&nbsp;nFaces          5590;  
&nbsp;&nbsp;&nbsp;&nbsp;startFace       5446;  
}  
wall-8  
{  
&nbsp;&nbsp;&nbsp;&nbsp;**type            wall;**  
&nbsp;&nbsp;&nbsp;&nbsp;**inGroups        1(wall);**  
&nbsp;&nbsp;&nbsp;&nbsp;nFaces          122;  
&nbsp;&nbsp;&nbsp;&nbsp;startFace       11036;  
}  
wall-4  
{  
&nbsp;&nbsp;&nbsp;&nbsp;**type            wall;**  
&nbsp;&nbsp;&nbsp;&nbsp;**inGroups        1(wall);**  
&nbsp;&nbsp;&nbsp;&nbsp;nFaces          101;  
&nbsp;&nbsp;&nbsp;&nbsp;startFace       11158;  
}    
