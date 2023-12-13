## Data compression and compressed data structures

Lecturer: Giovanni Manzini,
Computer Science Dept. University of Pisa.


### Tentative lesson plan: 

1. Statement of the lossless data compression problem. Kraft inequality.  Order-0 Entropy. Optimal codes, Huffman codes and arithmetic coding (22/11).
2. Beyond order-0 Entropy: MTF + gamma codes. Order-k entropy. PPM algorithms (24/11).
3. LZ77 parsing: definition, bounds in terms of the order-k entropy. Introduction to the Burrows-Wheeler transform (27/11).
4. Compression bounds for the BWT. Introduction to compressed indices (29/11).
5. Wavelet Trees for efficient rank operations. Rank/Select operations on bitvectors (4/12).
6. Practical bitvector implementations. Compressed bitvectors (RRR representation). Finding the position of the occurrences in a BWT index: uniform sampling and the r-index (6/12).
7. Locate in the r-index (end). Subpath queries in Graph: conditional lower bound. (13/12).
8. Wheeler Graphs.(15/12)


**All lectures are 9am-11am in Sala Seminari EST (Room 351).** There will be no streaming or recording of the lectures. 
 


### There are two possible exam formats:

1. Students can present a problem/idea related to their research and show how it can take advantage of the techniques described in the course; this must include a working prototype of the suggested solution.

2. Students can present a related to the course using materials provided by the instructor. 

3. All the exams should be given no later than 31/5/2024.


### Study material

* [Book: Cover, Thomas. *Elements of Information Theory*](https://archive.org/details/ElementsOfInformationTheory2ndEd), Chapter 5 covers Kraft inequality and Huffman Coding.

* [Paper on MTF encoding](/data-compression/papers/mtf.pdf)

* [Paper: LZ parsing and entropy](/data-compression/papers/sicomp00.pdf). In-depth analysis of LZ77 and LZ78 algorithms, a little bit technical.

* [Slides: introduction to the BWT](/data-compression/slides/BWTintro.pdf)

* [Slides: searching using the BWT](/data-compression/slides/BWTindex.pdf)

* [Slides: introduction to Wavelet Trees](/data-compression/slides/WaveletIntro.pdf)

* [Paper: Optimized succinct data structures for massive data](https://doi.org/10.1002/spe.2198). Bitvector implementations from the authors of the [sdsl library](https://github.com/simongog/sdsl-lite).

* [Paper: FM-index for dummies](https://doi.org/10.1007/978-3-319-58274-0_16). Description and experiments of a simple BWT-index. 




### Possible exam material 


Some topics can be studied by two people that will prepare a joint presentation. Regardless of the topic, each student should give a 30 minute presentation describing: 1) the problem, 2) the previous state of the art, 3) the content of the new contribution. Tentative list of topics:

* [Asymmetric Numeral Systems](https://doi.org/10.1145/3397175): the evolution of arithmetic coding (assigned to MR + ?)
* [Analysis of a Suffix Array construction algorithm](https://doi.org/10.48550/arXiv.1710.01896)
* Parametrized pattern matching: [the latest solution](https://doi.org/10.1016/j.ipl.2020.106026) and some [background material](https://doi.org/10.1016/j.dam.2018.07.017) 
* [Applications of Wavelet Trees](https://doi.org/10.1016/j.jda.2013.07.004) (assigned to AJ)
* [Wavelet matrix](https://doi.org/10.1016/j.is.2014.06.002): an alternative layout for Wavelet Trees 
* [Tunneling on BWTs and Wheeler Graphs](/data-compression/papers/baier_thesis.pdf) (2 people)
* [Range Minumum](https://doi.org/10.1137/090779759) and [other queries](https://link.springer.com/10.1007/978-3-031-20624-5_5) (2 people)
* [An index based on LZ-parsing](https://doi.org/10.1016/j.tcs.2012.02.006) (2 people)
* [Universal index based on the concept of attractors](https://doi.org/10.1016/j.tcs.2018.09.007) (2 people)
* [Grammar compression and indexing](https://doi.org/10.1016/j.jcss.2020.12.001) (2 people)
* [Succinct Trees](https://doi.org/10.1145/2601073)  (2 people)

All papers should accessible using the department account: contact me if you have any problem. 