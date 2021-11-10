MashMap, modified to always use window size 1

### Installation

First, and *separately* clone the original MashMap from
https://github.com/marbl/MashMap and follow the instructions for installation
there. As part of this, you will produce a Makefile suitable for your machine.

Second, clone this repository, https://github.com/medvedevgroup/MashMap, and
copy the Makefile (from your installation of the original MashMap) into this
directory. Then follow the remaining installation steps from the original
MashMap.

### How this differs from the real MashMap

A small change has been made in src/map/include/parseCmdArgs.hpp so that it
will always set the window size to 1.

