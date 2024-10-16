# FD-Gen Beta Version 0.1
## Release Notes

**Release Name**: FD-Gen Beta 0.1

**Release Date**: [Oct 15, 2024]

**Version**: 0.1 (Beta)


## Getting started
**Fire data generator (FD-Gen)** is a Python-based script tool designed to automate the creation of multiple FDS input files.
The tool is developed using the Python programming language. It reads parameters and commands from a text file that integrates FD-Gen syntax into an FDS input file template, enabling seamless customization and automation in the creation of FDS input files.


The workflow of FD-Gen is shown below. It consists of 6 main steps.

![Figure 1. FD-Gen framework.](images/Picture1.png)

**Figure 1.** FD-Gen framework.


## Usage example 

### step 1: create the FD-Gen input file.

To prepare the FD-Gen input file.
Each data generation project in FD-Gen is controlled by a paragraph of text-based script embedded within the original FDS input file. 
This script employs a namelist format to input parameters and values throughout the entire data generation process. 
This structured approach allows for clear organization and efficient manipulation of the fire parameters, facilitating seamless integration with the FDS framework.

The following folder contains several examples of prepared FD-Gen input files.

[**FD-Gen Input File Examples**](https://github.com/hqfang3/FD-Gen/tree/main/example)

### step 2: analyze the input file with FD-Gen.



### step 3: check the parameter sampling data.



### step 4: wrap the FDS input file.



### step 5: acquire the outputs.



