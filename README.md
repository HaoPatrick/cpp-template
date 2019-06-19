# Template to bootstrap C++ research projects

[![Build Status](https://dev.azure.com/xha62/xha62/_apis/build/status/HaoPatrick.cpp-bootstrap?branchName=master)](https://dev.azure.com/xha62/xha62/_build/latest?definitionId=2&branchName=master)

> this language (C++) has many dark corner, stupid conventions, implicit conversion and not mention UB 
> -- [Wojciech Muła](http://0x80.pl/notesen/2015-05-25-tricky-mistake.html) 

Context: my research focus is high performance computing

## Features

- GTest + Spdlog

- Modern CMake

- C++ 17

- Sanitizers enabled in Debug mode, `march=native` in Release mode.

- Docker enabled

- CI included

- Clang-format: Google style

## Build

```bash
mkdir build && cd build
cmake -DCMAKE_BUILD_TYPE={Debug|Release} ..
make -j
```
