## Matlab CEC2013 Benchmark Functions For MacOS 

*Organizers : Xiaodong Li, Andries Engelbrecht, and Michael G. Epitropakis*

*Version : 1.2*

*Developers : Michael G. Epitropakis and Xiaodong Li*

Please refer to:

- https://titan.csit.rmit.edu.au/~e46507/cec13-niching/
- https://titan.csit.rmit.edu.au/~e46507/cec13-niching/competition/

#### 1、Changes:

1. Remove the header file of "windows.h"
2. Replace "malloc.h" with "stdlib.h"
3. Replace all "%Lf" with "%lf"

#### 2、How to compile:

Run the following command in Matlab window:

```matlab
mex cec13_func.cpp
```