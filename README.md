# AoC-starter
Starter code for Advent of Code for C++

## Prerequisites
Before you start installing things, check what you have:
```shell
> gcc --version
```

## How to use
Prepare a problem for a day with:
```shell
scripts/prepare [day_number]
```
Run a problem with:
```shell
scripts/run [day_number]
```

## Project Structure
```
├───.build                # CMake will generate and build the project here
├───.vscode               # Contains tasks and recommended extensions
├───cmake                 # Contains some files used by CMake
├───scripts               # Contains all the scripts
├───input                 # Contains all input files
└───src                   # Cintains all the source cpp files with your code
```
