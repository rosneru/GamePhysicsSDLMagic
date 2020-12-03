# README #

##  Overview ##
The aim for this project is

1. To learn a little SDL programming following [this tutorial](http://lazyfoo.net/tutorials/SDL/index.php)
2. To learn about game physics from the book *Game Physics Engine Development* by *Ian Millington*


## Development environment ##

Currently it is a Visual Studio 2019 / C++ solution.

The solution expects the extracted [SDL 2.0.12 developers archive](https://www.libsdl.org/download-2.0.php)
(platform Win32/64) at the location

    c:\Development\Cpp\SDL2-2.0.12\

To run the compiled binaries the following path must be added to Windows
environment variable for **System** (not e.g. for *user Administrator*)

    c:\Development\Cpp\SDL2-2.0.12\lib\x64\

Only then the SDL2.dll is found at runtime.
