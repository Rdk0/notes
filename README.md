Author: Conner McDaniel - "Note and citation system with vim and pandoc" https://www.youtube.com/watch?v=nXgqnYVAzKk&t=8s
https://github.com/connermcd

modied by Rdk0 nov 29, 2024 to add the journal name to the title 

notate2 - processes one pdf at a time
example 
./notate2 /path/file.pdf generates two files in the same directory, for example "Zhao_2022_Pharmaceuticals.pdf" and "Zhao_2022_Pharmaceuticals.md".  The .pdf just replaces file.pdf

runall - iterates over all pdfs in a given directory and uses notate2 for processing
