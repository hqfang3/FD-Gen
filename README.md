# FD-Gen Beta Version 0.1
## Release Notes
Fire data generator (FD-Gen) is a Python-based script tool designed to automate the creation of multiple FDS input files.

**Release Name**: FD-Gen Beta 0.1

**Release Date**: [Oct 15, 2024]

**Version**: 0.1 (Beta)

# Fire data generator (version 0)
## Introduction
This document describes how to generate multiple FDS input files and preprocees the data from FDS outputs for machine learning model development. 

## Environment requirements
  python==3.11.5
  
  numpy==1.21.0
  
  pandas==2.1.4
  
  scipy==1.11.4
  
  matplotlib==3.8.0

## Main code
### Part 1 - Parameter sampling
sampling.py: To define parameters for sampling and output the data as a spreadsheet and a .pkl file
  - N: Number of samples
  - random.seed(): give the seend number
