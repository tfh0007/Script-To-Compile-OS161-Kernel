# Script To Compile OS161 Kernel
This script was designed for helping with Project 2 COMP 3500: An Introduction to OS/161
This Script is to be used on Linux based machines. The script when executed will automatically configure, build, and launch the sys161 kernel utility for OS161.

This script requires 1 parameter which is the compile location

Typically the compile locations are ASST and then a number
The script needs to be executed in a bash based window, such as terminal.
If the os prevents execution of the script (autoCompileKernel) then permissions will need to be allowed

To allow permissions you can use chmod
For a regular user 
$ chmod u+x autoCompileKernel
should be enough

Once permissions are estabilished the script can easily be run with 
$ ./autoCompileKernel [compile_location]






