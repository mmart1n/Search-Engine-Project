# Search Engine Project
Program your own (command-line based) Information Retrieval system using Apache
Lucene 7.4 and Java 8. Lucene is an open source search library that provides
standard functaionality for analayzing, indexing, and searching text-based documents.

### Requirements
The following criteria have to be met by your Information Retrieval system. Your program
should:
1. Using Lucene, parse and index Plain Text and HTML documents that a given folder
and its subfolders contain. List all parsed files.
2. Consider the English language and use a stemmer for it (e.g. Porter Stemmer)
3. Select an available search index or create a new one.
4. Print a ranked list of relevant articles given a search query. The output should
contain the most relevant documents, their rank, path, last modification time,
relevance score and in addition for HTML documents title and summary.
5. Search multiple fields concurrently: not only search the document’s text (body tag),
but also its title and date (for HTML documents).

The program should be written in a way that it is runnable without taking any look in
the source code or even adapting the source code. Create a jar-File named IR P01.jar. It
should process the input in the format as shown below:

java -jar IR P01.jar [path to document folder]
