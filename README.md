# GTFS-Realtime Autodoc

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/)

## Purpose
GTFS-Realtime is a an efficient means for interchange of large amounts of data on the state of a public transport network. The combination of its efficiency and implementation result in a product that is difficult to understand for newcomers. This is made even worse by the fact that the documentation is intermixed with [code](https://developers.google.com/transit/gtfs-realtime/gtfs-realtime-proto).

This repository presents the same information (along with several extensions) as hypertext, which may be easier to understand. See that documentation [here](https://laidig.github.io/gtfs-rt-autodoc/index.html).

## Contributions
There are other extensions out there. Submit a Pull Request if you would like them included.

# Re-generation
This documentation was generated with Doxygen. To regenerate, add or modify the .proto files in the root directory and run
  
    doxygen doxyfile

## Credits
This would not have been possible without:
* [Google](https://developers.google.com/transit/gtfs-realtime/), who shared the master .proto file under the Apache license
* [OVAPI](http://ovapi.nl), who shared their extension under the CC-BY-3.0 license
* [Doxygen](http://www.stack.nl/~dimitri/doxygen/)
* [Doxygen-Bootstrapped](https://github.com/Velron/doxygen-bootstrapped)

