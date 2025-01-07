Author: Conner McDaniel - "Note and citation system with vim and pandoc" https://www.youtube.com/watch?v=nXgqnYVAzKk&t=8s
https://github.com/connermcd

modied by Rdk0 nov 29, 2024 to add the journal name to the title and files for batch processing: runall, renameamp, removespace"

notate2 - processes one pdf at a time

Example

./notate2 /path/file.pdf generates two files in the same directory, for example "/path/Zhao_2022_Pharmaceuticals.pdf" and "/path/Zhao_2022_Pharmaceuticals.md".  The .pdf just replaces file.pdf

runall /path/dir - iterates over all pdfs in a given directory and uses notate2 for processing

renameamp /path/dir - replaces "amps;" present in some journal names with "and" for all .md and .pdf files in directory

removespace /path/dir - replaces all spaces in files ending with .md and .pdf files in directory
