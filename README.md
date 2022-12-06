# SEI_SRC_TO_UML
Git Repo of TAMUSA class Software Engineering 1 project.

# Python To UML
A script to convert python code into a UML-style class Diagram. 

This script will produce a grahviz vocde that can be piped into graphviv engine

 Currently:
 
     find src/ -type f -iname "*.py"  | xargs python py2uml.py | dot -T png -o test.png
 
 The above command above should be used from the directory where the file will be normally executed (This is important so the necessary imports are correct and located in your file).
 
 Note that your code must compile in order to use (files will be imported).
 
 ## Example 
 
