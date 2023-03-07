# Simple PDF Highlighter

This code allows you to get words from a pdf and highlight the text from the command line. It's not very verbose, as I only spent two days working on it.
The syntax is as follows:

python pdf_highlighter.py -i INPUT -o OUTPUT -s STRING

where INPUT is the input file for parsing, OUTPUT is the name of the finished file will be saved as, 
and STRING is the string of text that will be highlighted. Currently it uses Regex so it will find and highlight all words that match the pattern.
