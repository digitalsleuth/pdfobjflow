# pdfobjflow
Python script to create an object flow of PDF data input from pdf-parser

The original source for this script is from Sebastien Damaye @ https://bitbucket.org/sebastiendamaye/pdfobjflow/src/master/

This program is meant to be used with pdf-parser from Didier Stevens. It reads the output from pdf-parser and creates the map of the objects flows under the form of a DOT file. You can then use the dot utility to export an image (e.g. PNG file).

It has been updated for use with python3 and the python3 pydot tool.
