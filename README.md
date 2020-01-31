# Clang Hello

A trivial example of compiling C++ with Clang


```
docker build -t hello_clang - < Dockerfile
docker run -it -v <project root>:/code:cached -w /code hello_clang /bin/bash
clang++ main.cpp
./a.out
```
