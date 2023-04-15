# Concordance 4

### Overview
Concordance algorithm in Python 3 generates a formatted and sorted output.

### Algorithm Steps:
- Takes input through *.txt* file;
- Identifies and stores **exclusion words** and **body text**;
- Calculates keywords by **matching** non-exclusion words with body text;
- Locates keyword occurances;
- Formats output by **aligning keywords** and **removing excess context**;
- Result is output through *.txt* file.

### Text Concordance
Concordance algorithms, also known as keyword in context algorithms, analyze the words surrounding a given word to determine its context. The Concordance 4 algorithm focuses on all the words in the body text that are not part of the exclusion words list, which are called query words. For example, if the query word is "apple," and the sentence is "An apple fell beside me," the raw output before formatting would be "An APPLE fell beside me."

However, Concordance 4 takes the concept further by improving the output's readability and consistency. Specifically, it sorts all query words lexicographically and aligns them in columns. The Concordance 4 program is a valuable tool for data analysis applications because it not only identifies the frequency of a given word but also the context in which the word is used. This technique can provide significant insight into large datasets, which would otherwise be hidden.

To ensure the Concordance 4 program's maintainability and ease of debugging, it employs efficient software engineering practices, such as low coupling and high cohesion. The program decomposes larger functions into smaller helper functions, each with specific documentation. This approach will help create maintainable code and facilitate future debugging.

Overall, Concordance 4 is an effective and efficient algorithm that can provide valuable insights into large datasets by analyzing the context of individual words.

### Running the program
`./driver-new.py --in [input_file].txt --out _[output_file].txt`
