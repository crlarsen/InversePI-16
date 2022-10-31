# Prototype binary16 reciprocal circuit using Python 3

## Description

Compute binary16 floating point reciprocal using Newton's Method. The code is written using Python. The code marks the location of the binary point, and avoids the numerical instabilities which occur in the C++ version of the code.

The code is a quick and dirty hack. It IS NOT production quality code. Use at your own risk.

The code is known to produce inaccurate results in the last bit, or two of the result. It is strictly "Proof of Concept" code.

The code is explained in the video series [Building an FPU in Verilog](https://www.youtube.com/playlist?list=PLlO9sSrh8HrwcDHAtwec1ycV-m50nfUVs).
See the video *Building an FPU In Verilog: Floating Point Division, Part 4*.

## Manifest

|   Filename   |                        Description                                  |
|--------------|---------------------------------------------------------------------|
| README.md    | This file.                                                          |
| InversePI-16 | Python 3 script to compute and round reciprocal of binary16 values  |

## Copyright

:copyright: Chris Larsen, 2022
