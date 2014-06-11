OpenGL
======
Tutorial 1. Setting Up Working Environment. 
To begin working with OpenGL in Microsoft Visual Studio 2012 you need to download and install the following libraries: 
1.	freeglut 2.8.1-1.mp for MSVC  (can be downloaded from here: http://www.transmissionzero.co.uk/software/freeglut-devel/)

2.	 glew-1.10.0WIN32 (ZIP archive can be downloaded from here:  http://glew.sourceforge.net/)
Copy both unzipped folders into a new directory accessible by all users, for example C://graphics ( you may choose your own folder name and location). Follow the instructions in readme.txt files for package installation and set up project properties in Visual Studio 2012 like so: 

Project -> Project Properties -> Configuration Properties -> VC++Directories-> IncludeDirectories:

C:\graphics\glew-1.10.0WIN32\bin\Release\Win32
C:\graphics\glew-1.10.0WIN32\lib\Release\Win32
C:\graphics/glew-1.10.0WIN32\include
C:\graphics\freeglut\include

