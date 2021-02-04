# Script To Compile OS161 Kernel
This script was designed for helping with Project 2 COMP 3500: An Introduction to OS/161
This Script is to be used on Linux based machines. The script when executed will automatically configure, build, and launch the sys161 kernel utility for OS161.
This script requires 1 parameter which is the compile location
This Script assumes the compile location is located at 

~/cs161/src/kern/compile/[compile_director]


If this is not the compile location then the default location will need to be changed in the autoCompileKernel script.
The default location can be changed in the fith line (In The if statement). Also the if statement (3rd line) will need to be updated with that location as well otherwise the program will always give an error because it can not find your parameter in ~/cs161/src/kern/compile/[compile_director]



Typically the compile locations are ASST and then a number
The script needs to be executed in a bash based window, such as terminal.
If the os prevents execution of the script (autoCompileKernel) then permissions will need to be allowed

To allow permissions you can use chmod. For a regular user: 

  $ chmod u+x autoCompileKernel

should be good enough.

Once permissions are estabilished the script can easily be run with 

  $ ./autoCompileKernel [compile_location]

Lets assume this repository exists in the default Downloads folder and we want to compile ASST0:
To run the script type:


$ ~/Downloads/ScriptToCompileOS161Kernel/./autoCompileKernel ASST0




