# Installation

First, we need to install `cmake` on your system. This is done differently depending on your operating system.

### For Ubuntu

`$ sudo apt-get install cmake`

### For Redhat

`$ yum install cmake`

### For Mac OS X with Macports

`$ sudo port install cmake`

# Build

Build `test.cpp` program using cmake by running the following commands:

```
$ cmake -H. -Bbuild
$ cmake --build build -- -j3
```

# Run

`$ ./bin/hello`

Output: Hello World
