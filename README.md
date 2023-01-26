# Concordance-4
Text concordance algorithm in Python3 that generates formatted and lexicographically sorted output.

Algorithm takes ".txt" input specifying exclusion words (i.e. words not to be indexed by algorithm) and body text to be processed and sorted via concordance specification. This output is written to a specifed ".txt" output file.

Concordance (aka keyword in context) algorithms determine context on either side of a given word. The Concordance-4 evaluates all words found in body text that are not found in exclusion words. These words are know as query words. For example, say the query word is "apple", and the sentence is "an apple fell beside me", the raw output prior to formatting would be "an APPLE fell beside me". Concordance-4 improves upon this idea by further formatting the output. All query words are lexicographically sorted and collumn aligned in order to provide a readable and consistent output.

The idea of concordance proves to be incredibly useful in data analysis applications as it not only identifies how many times a given word is used, but also the context in which the word is used. This can provide great insight into large data sets which are often hidden when such technique is not used.

My Concordance-4 program uses efficient software engineering practices such as low coupling and high cohesion by decomposing larger functions into smaller helper functions with specific documentation. This will lead to maintainable code and easy debugging in the future.
