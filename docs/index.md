## Data compression and compressed data structures

Lecturers: Giovanni Manzini, Paolo Ferragina. 
Computer Science Dept. University of Pisa.

### Tentative lesson plan: 

1. Statement of the Data compression problem. Main ideas beyond compression techniques: symbol substitution, phrase encoding, data transformations. Kraft inequality (16/5)
2. Consequences of Kraft Inequality. Order-0 Entropy. Optimal codes, Huffman codes. Oder-k entropy PPM algorithm. LZ77 parsing, definition, bounds in terms of the order-k entropy (17/5)
3. Burrows-Wheeler transform, relation with k-order entropy. Compression boosting (18/5)
4. Beyond entropy: others measures of compressibility (25/5)
5. Introduction to compressed indices and Wheeler Graphs (26/5)
6. Compressed indices for highly repetitive collections (r-index) (27/5)
7. Predecessor search: models of computation and various contexts of application. Binary Search. The case of bounded universe: x-fast trie and y-fast trie. The case of uniform key distributions: interpolation search with complexity evaluation. (30/5)
8. Elias-fano coding with constant time access. Learned data structures (31/5)

**All lectures are 9am-11am in Sala Seminari EST (Room 351).**
Streaming will be available on Google Meet: email me for the link. Lectures will not be recorded. 


### There are two possible exam formats:

1. students can present a problem/idea related to their research and show how it can take advantage of the techniques described in the course, possibly including a prototype of the suggested solution

2. students can present a related topic not covered in the course using materials provided by the instructors


### Study material

* [Slides lectures 1 & 2](/data-compression/blob/main/docs/slides/1DataCompressionAndEntropy.pdf) 

* [Book: Cover, Thomas. *Elements of Information Theory*](https://archive.org/details/ElementsOfInformationTheory2ndEd), Chapter 5 covers Kraft inequality and Huffman Coding.

* [Paper: LZ parsing and entropy](/data-compression/blob/main/docs/papers/sicomp00.pdf). In-depth analysis of LZ77 and LZ78 algorithms, a little bit technical.

* [Slides: Introduction to the BWT](/data-compression/blob/main/docs/slides/BWTintro.pdf)

* [Paper: A "simple" analysis of BWT+MTF+Order0](/data-compression/blob/main/docs/papers/BWTanalysis.pdf) 

* [Slides](/data-compression/blob/main/docs/slides/BWTboosting.pdf) and [full paper](/data-compression/blob/main/docs/papers/boosting.pdf) on Compression boosting with the BWT

* [Paper on Repetitiveness Measures](/data-compression/blob/main/docs/papers/repetitivenessMeasures.pdf). Note that the proof of inequality $\gamma \leq b$ at page 19 is incorrect: to build an attractor you need to take the first position of each phrase.

* [Slides](/data-compression/blob/main/docs/slides/BWTindex.pdf) on BWT-based indices

* [Slides](/data-compression/blob/main/docs/slides/WG.pdf) on Wheeler Graphs/Automata

* [Paper on the R-index](/data-compression/blob/main/docs/papers/rindex.pdf)

* [Slides](/data-compression/blob/main/docs/slides/xy-fast_trie) on x-fast and y-fast tries

* [Book on algorithm engineering](https://www.dropbox.com/s/b3bu01nyz8zkqmi/Algorithm_Engineering_Book.pdf?dl=0). The relevant sections are: the Prologue, Sect. 9.2 (interpolation search), Sect. 11.6 (Elias-Fano).

* [Paper on the index described in the last lecture](http://www.vldb.org/pvldb/vol13/p1162-ferragina.pdf)

* [Review on learned data structures](http://learned.di.unipi.it/publication/learned-data-structures/learned-data-structures.pdf)



### Students' presentations

| Name | Topic | Date |
| --- | --- | ---|
| Antonio Boffa    | Compressing ultra-large source code datasets using locality-sensitive hashing | **29-07** |
| Cosimo Rulli     | Neural networks compression | **14-07** | 
| Daniele Atzeni, Francesco Tosoni  | Neural networks compression for edge devices | |
| Federica Baccini | Graph Compression | **27-07**|
| Lorenzo Catania  | Compression of genomic datasets via INR |  **26-07** |
| Domenico Tortola | On the compression of blockchain | **27-07** |
| Luca Corbucci, Rudy Semola | Neural network-based compression | **28-07** |
| Alessandro Bocci | EEG compression | **28-07**|
| Andrea Guerra | A heuristic for the packaging of source code in Software Heritage |  |
| Domenico Tortorella |  | |


