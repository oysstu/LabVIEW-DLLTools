# LabVIEW-DLLTools
Various utilities for easier integration of LabVIEW with C/C++.
For now, this is simply a set of tools used for my personal projects, and is not very polished.

### Current features
* Template class for nd-array data (array handles).
* Wrapper around array template type for resizing
 * Numeric array handles
 * Array of array handles
 * Cluster data array handles (when declared with correct byte packing)
* Runtime exception class for returning exceptions to a LabVIEW error cluster

### Requirements
* C++11 compatible compiler (VS2013 or newer will suffice)
 
### Future plans
* Examples for every feature
* Implement as header-only library
* Implement utility for exchanging dynamically typed data
* Implementation of LVString and tools that operate on that type