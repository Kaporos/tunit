# TUNIT

Tunit is a really simple and lightweight testing library written in C.
It is contained in only *one* file, `tunit.h`

![hey](https://github.com/Kaporos/tunit/assets/34960023/0e7e794e-88ad-493c-bdc0-446e5452fd47)



## Features

- Basic assert between numbers
- Tests suites
- Pass values to tests


## Usage

Currently this project is still a WIP, please take a look at `main.c` which contains a demo of the actual state of the lib.


To use it, just add `tunit.h` in your project directory and put this in your main.c:

```c
#define TUNIT_IMPLEMENTATION
#include "tunit.h"
```

