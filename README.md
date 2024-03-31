# Project: QT_OpenGL_Window

## Overview

This project deals with the triangulation of data obtained from STL files. The key components of the project are as follows:

- **Source Files**: 
  - `point3D.cpp`
  - `triangle.cpp`
  - `triangulation.cpp`
  - `reader.cpp`
- **Header Files**: 
  - Located in the `headers` folder, containing declarations for the source files.
- **Functionality**:
  - `reader.cpp` reads data from STL files, extracting points and storing them in triangulation vectors.
  - Triangulation algorithms are implemented in `triangulation.cpp`.
  - `main.cpp` utilizes the triangulated data, creating vertices arrays for OpenGL rendering.
  
-  **Input**:
   - When prompted, provide the path to the input STL file.

-  **Visualization**:
   - The program will visualize the triangulated points using OpenGL.

## Output ScreenShot-
1. Cube
   ![Screenshot (76)](https://github.com/ombothe08/QT_OpenGL_Window/assets/158052399/45a30546-5535-43a2-a53e-305830814951)

2. Sphere
   ![Screenshot (77)](https://github.com/ombothe08/QT_OpenGL_Window/assets/158052399/4630fd8f-1ba2-49e9-b4be-da9aa9691c16)
