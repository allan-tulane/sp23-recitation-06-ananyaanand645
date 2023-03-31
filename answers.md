# CMPS 2200 Recitation 6
## Answers

**Name:** Ananya Anand


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt |   1340  |    826  | 0.61
alice29.txt  |  1039367 | 676374 | 0.65
asyoulik.txt |  876253 |  606448 | 0.69
grammar.lsp | 26047 | 17356 | 0.67
fields.c    | 78050|56206  | 0.72




- **e.**
- If every character in a document has the same frequency, then the Huffman encoding for the document would be a binary tree with all leaves at the same level.As a result, the Huffman algorithm would greedily combine the two least frequent characters into a single node until all characters are combined into a single node at the root of the tree. This tree would have $n$ leaf nodes.

Therefore, the expected cost of a Huffman encoding for a document in which every character has the same frequency is the same as the cost of encoding a single character using a Huffman code with a binary tree of depth 1, which is 1. 



