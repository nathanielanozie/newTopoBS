newTopoBS
=========

save old blendshapes given have a new topo mesh projected onto old base mesh

I wrote this tool to help reuse work done on old blendshapes on a new topo mesh.  It works pretty well on fairly low resolution facial meshes say (6000 triangles or less).
Its main assumption is that user has a way of getting the new topology mesh to be projected as close as possible onto the old base mesh.
The code in the main file can be used for a Maya python shelf.

Usage:

1.First run the main.py.  It should give directions.  The result of this is a command to be run in python editor.

2.When you've created the python command to generate new topo meshes,  select one old blendshape at a time 
then run the python command (should take a couple minutes on low res mesh).

Known Bugs:
For hi res face meshes its pretty slow.  Running on more than one selected bs at a time is'nt as stable as running on a single selected bs.


Cheers,

Nathaniel Anozie

nathananozie dot blogspot dot com
