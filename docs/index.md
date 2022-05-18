## Data compression and compressed data structures

Lecturers: Giovanni Manzini, Paolo Ferragina. 
Computer Science Dept. University of Pisa.

### Tentative lesson plan: 

1. Statement of the Data compression problem. Main ideas beyond compression techniques: symbol substitution, phrase encoding, data transformations. Kraft inequality (16/5)
2. Consequences of Kraft Inequality. Order-0 Entropy. Optimal codes, Huffman codes. Oder-k entropy PPM algorithm. LZ77 parsing, definition, bounds in terms of the order-k entropy (17/5)
3. Burrows-Wheeler transform, relation with k-order entropy. Compression boosting (18/5)
4. Beyond entropy: others measures of compressibility. Introduction to compressed indices. Wheeler Graphs (25/5)
5. Rank and select operations. Wavelet trees and some applications (26/5)
6. Compact representation of tree, graphs, and other structures (27/5)
7. Compressed indices for genomic datasets (30/5)
8. Learned data structures (31/5)

**All lectures are 9am-11am in Sala Seminari EST (Room 351).**
Streaming will be available on Google Meet: email me for the link. Lectures will not be recorded. 


### There are two possible exam formats:

1. students can present a problem/idea related to their research and show how it can take advantage of the techniques described in the course, possibly including a prototype of the suggested solution

2. students can present a related topic not covered in the course using materials provided by the instructors


### Study material

* [Slides lectures 1 & 2](/data-compression/slides/1DataCompressionAndEntropy.pdf) 

* [Cover, Thomas. *Elements of Information Theory*](https://archive.org/details/ElementsOfInformationTheory2ndEd), Chapter 5 covers Kraft inequality and Huffman Coding.

* [LZ parsing and entropy](/data-compression/papers/sicomp00.pdf). In-depth analysis of LZ77 and LZ78 algorithms, a little bit technical.

* [Introduction to the BWT](/data-compression/slides/BWTintro.pdf)

* [A "simple" analysis of BWT+MTF+Order0](/data-compression/papers/BWTanalysis.pdf) 

* [Compression boosting with the BWT](/data-compression/slides/BWTboosting.pdf), [full paper](/data-compression/papers/boosting.pdf)


