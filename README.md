# JavaEbookReader


This app parses text from a dictionary file and text from a google
file which are embedded in the app. It then crosses the information from both files and writes a
new file called index.txt with the information from the dictionary
file that doesn't appear in the Google file.
The application then parses the information from an enbedded eBook and reads
the index.txt and once again crosses this information. If any of the
words in the eBook file matches the first word of each line from the
Indexer.txt, it writes this information into a new file called
definition.txt.

The application has a counter that creates a page every 40 lines of
text.
