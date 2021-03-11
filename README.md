# PyCompiler++ Also Known As PYC++ (Fork)
 PyCompiler++ is a python compiler built to compile Panda3D games, and to prevent source code dumps, and code injection.
 
 # Fork
 * This fork will serve as an analysis of the original project.

# Requirements:
* Cython
* CX_Freeze
* Panda3d

# How it works:
* PYC++ Converts the set modules into c++, then it compiles the modules into a .pyd file. Then PYC++ compiles a __main__ also specified, into an exe which decrypts the .pyd and runs the game.
* Please Note: The compiler is in heavy development, don't expect perfect results!

# Original Author to whom this project was written by:
* SkippsDev / Caleb Marshall (https://www.github.com/cmarshall108)

# Original Uploader of the project to which this fork is based on:
* Toonerz (https://www.githuib.com/Toonerz)
