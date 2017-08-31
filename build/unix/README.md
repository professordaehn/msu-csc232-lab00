# Using `cmake`

## Compiling with `g++`

```bash
$ g++ *.cpp
$ g++ *.cpp -std=c++14
$ g++ Main.cpp -std=c++14
$ ./a.exe
$ rm ./a.exe
$ g++ Demo.cpp -std=c++14
 ```

## Unix make files

Typing

```bash
cmake -G "Unix Makefiles" ../..
```

at the command line prompt will, among other things, generate a `Makefile` that can be used by a program named `make` to compile and build executables.

The argument to cmake following the `-G` switch specifies the type of project files to generate.

For example, here are a number of others:

```bash
Generators
  Unix Makefiles               = Generates standard UNIX makefiles.
  Ninja                        = Generates build.ninja files.
  CodeBlocks - Ninja           = Generates CodeBlocks project files.
  CodeBlocks - Unix Makefiles  = Generates CodeBlocks project files.
  CodeLite - Ninja             = Generates CodeLite project files.
  CodeLite - Unix Makefiles    = Generates CodeLite project files.
  Eclipse CDT4 - Ninja         = Generates Eclipse CDT 4.0 project files.
  Eclipse CDT4 - Unix Makefiles= Generates Eclipse CDT 4.0 project files.
  KDevelop3                    = Generates KDevelop 3 project files.
  KDevelop3 - Unix Makefiles   = Generates KDevelop 3 project files.
  Kate - Ninja                 = Generates Kate project files.
  Kate - Unix Makefiles        = Generates Kate project files.
  Sublime Text 2 - Ninja       = Generates Sublime Text 2 project files.
  Sublime Text 2 - Unix Makefiles
                               = Generates Sublime Text 2 project files.
```
