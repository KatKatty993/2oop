This C++ program provides a comprehensive set of classes for working with various 2D and 3D geometric shapes, allowing users to create shapes and calculate their properties.
Features

    2D Shapes:
        Square (Rectangle)
        Equilateral Triangle
        Regular Pentagon
        Regular Hexagon
        Circle
        Regular Polygon (n-sided)

    3D Shapes:
        Cube
        Tetrahedron
        Octahedron
        Dodecahedron
        Icosahedron
        Sphere

    Calculations:
        Area (for 2D shapes)
        Perimeter (for 2D shapes)
        Volume (for 3D shapes)
        Inscribed and circumscribed radii
        Face properties (for 3D shapes)

How to Use

    Compile the program using a C++ compiler (C++11 or later required)
    Run the executable
    Follow the on-screen instructions to create shapes and modify their properties
    
Available Commands
When working with a shape, you can use these commands:
    setSide <value> - Set the side length (or radius for circle/sphere)
    setArea <value> - Set the area (will adjust size accordingly)
    setPerimeter <value> - Set the perimeter (2D shapes only)
    setVolume <value> - Set the volume (3D shapes only)
    setInscribed <value> - Set the inscribed radius
    setDescribed <value> - Set the circumscribed radius
    getFace - Show face properties (3D shapes only)
    exit - Return to shape selection

Implementation Details
    Uses object-oriented programming principles
    Implements inheritance hierarchy (Shape → FlatShape/VolumeShape → specific shapes)
    Utilizes polymorphism with virtual functions
    Includes smart pointers for memory management
    Provides comprehensive mathematical calculations for each shape type

Example Usage

Shape Creator
Available shapes:
2D: square, triangle, pentagon, hexagon, circle, polygon
3D: cube, tetrahedron, octahedron, dodecahedron, sphere
Enter 'exit' to quit

Enter shape type and size: cube 5

Created shape:
Name: Cube
Side Length: 5
Sides: 12
Vertices: 8
Area: 150
Volume: 125
Faces: 6
Faces per Vertex: 3
Sides per Face: 4

Enter command (or 'help' for options): setVolume 1000
Updated shape:
Name: Cube
Side Length: 10
Sides: 12
Vertices: 8
Area: 600
Volume: 1000
Faces: 6
Faces per Vertex: 3
Sides per Face: 4

Requirements
    C++11 or later compatible compiler
    Standard Library headers:
        <iostream>
        <string>
        <cmath>
        <sstream>
        <memory>
        <algorithm> (implicitly used via max())
