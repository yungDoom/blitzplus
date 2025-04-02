BlitzPlus open source release.

To build BlitzPlus you will need:

* Visual Studio 2022. Install "Desktop development with C++" plus "MFC and ATL support" plus "ASP.NET and web development".

To rebuild:

1) Open blitzplus.sln in Visual Studio.

2) Select release config and rebuild the entire solution.

3) Select debug config and rebuild the blitzplus project only.

4) This will rebuild everything into the _release and _release/bin dirs. Feel free to delete .pdb and .ilk files here.

5) Note: This version of blitzplus uses the dynamic version of the fmod audio lib. When redistributing programs built with blitzplus_msvc2022, you will need to also include the fmod.dll file found in the _runtime/bin directory with your programs. This should be placed in the same directory as your program's executable.
