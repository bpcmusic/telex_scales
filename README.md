# table_builder
## scale generator for the TELEX modules

(c) 2021 bpcmusic; MIT Licensed

## Overview

This is a simple python script to allow the conversion of Scala scales into the TELEX format. Please be kind - it is ugly and was done quite quickly. ;)

## Steps to Use

1. Put some Scala scales in a subdirectory (I used "scl/" and found them at the Scala site: http://www.huygens-fokker.org/docs/scales.zip).
2. Reference the scales that you want in the order that you want in a text file; see "items.txt" for an example.
3. Run the "table_builder.py" script and reference your input file. For example: python table_builder.py -i items.txt
4. The script will output a "scales.cpp" file in your current directory.
5. Cut and paste the two parts of the output into the corresponding areas of the "Quantizer.cpp" and the "Quantizer.h" files in your Arduino project directory for the TELEX.
6. Deploy your updated code to your TELEX's teensy.

---

Good Luck!!