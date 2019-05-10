# Gerald-Heart-3D
A demo of interpolating Heart 3D using implicit surface reconstruction.
1. Install Microsoft Visual Studio 2017.
2. Install CLAPACK (f2c'ed version of LAPACK). 
3. Open Microsoft Visual Studio 2017. Open a new project with the name of your choice. 
4. Extract the "GeraldHeart3D.zip" and copy all the files to your newly created project. Drag the "main.cpp" and "CIsoSurface.cpp" file under Source Files as shown below:

https://i.imgur.com/VcQebbm.png

5. Link the important headers and libraries to your newly created project:

Libraries:
blas.lib 
clapack.lib
libf2c.lib

Headers:
blaswrap.h
clapack.h
f2c.h

6. Choose "Release" as your Solution Configuration and "x86" as your Solution Platform as shown below:

https://i.imgur.com/4MeF0de.png

7. Run the program and try to change the offset values for different shape outputs.

Tips: 
- Offset values can be edited by finding the "offset" variable in the code. 
- Please be sure to have 3D Builder, 3D Viewer, or any type of software to view generated 3D files.
