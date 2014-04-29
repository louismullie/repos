Hi! My name is Louis, and here are some of the most interesting projects that I have worked on.

###Natural Language Processing

**Treat**

Homepage: https://github.com/louismullie/treat
(Languages: C, Ruby)

Treat is the leading Ruby toolkit for natural language processing and computational linguistics. The Treat project aims to build a feature-complete language- and algorithm- agnostic NLP framework for Ruby.

**CoreNLP Ruby bindings**

Homepage: https://github.com/louismullie/stanford-core-nlp
(Languages: Java, Ruby)

This gem provides high-level Ruby bindings to the Stanford Core NLP package, a Java natural language processing toolkit. The bindings support tokenization, sentence segmentation, part-of-speech tagging, lemmatization, syntactical analysis, named entity recognition and coreference resolution.

**OpenNLP Ruby bindings**

Homepage: https://github.com/louismullie/open-nlp
(Languages: Java, Ruby)

This library provides high-level Ruby bindings to the Open NLP package, a Java machine learning toolkit for natural language processing. The bindings support tokenization, sentence segmentation, part-of-speech tagging, and named entity recognition.

**Sentence segmentation algorithm**

Homepage: https://github.com/louismullie/scalpel
(Languages: Ruby)

Scalpel is a novel rule-based sentence segmentation algorithm for Latin languages. It is fast and accurate, even on poorly formatted data. The key insight is that it is simpler and more efficient to find occurrences of periods that do not indicate the end of a sentence first, and subsequently attempt to segment the text.

**TextRank implementation**

Homepage: https://github.com/louismullie/graph-rank
(Languages: Ruby)

GraphRank is a Ruby implementation of the TextRank algorithms. TextRank is an algorithm for unsupervised keyword extraction and document summarization that demonstrates how the PageRank algorithm can be applied to textual data.

**Language generation with Markov chains**

Homepage: https://github.com/louismullie/emcee
(Languages: Ruby)

This library takes rap lyrics as an input and generates new rap lyrics using Markov chains. A Markov chain models the behaviour of a random process where the next state of the process depends only on the current state, and not on the sequence of events that preceded it.

###Cryptography

**Secure remote protocol implementation (RFC 5054)**

Homepage: https://github.com/symeapp/srp-client
(Languages: Javascript)

This library implements a Javascript client for the SRP protocol, as standardized in RFC 5054. The Secure Remote Password protocol (SRP) is an augmented password-authenticated key agreement (PAKE) protocol with several interesting properties.

**Password-authenticated Diffie-Hellman implementation (RFC 5683)**

Homepage: https://github.com/symeapp/pak-dh-client
(Languages: Javascript)

This library implements a Javascript client for password-authenticated key exchange. The protocol provides provides a secure, authenticated key-exchange with forward secrecy and resistance against offline dictionary attacks.

**Synthetic initialization vector implementation (RFC 5297)**

Homepage: https://github.com/cryodex/siv-rb
(Languages: C, Ruby)

This gem implements the AES-SIV mode of operation for deterministic authenticated encryption. The underlying cipher is written as a low-level C extension on top of OpenSSL, for speed and compatibility.

**Cipher-based message authentication code implementation (RFC 4493)**

Homepage: https://github.com/cryodex/cmac-rb
(Languages: C, Ruby)

This gem implements the AES-CMAC mode of operation for tamper-resistant message authentication. AES-CMAC achieves a security goal similar to that of 
HMAC, but relies on a symmetric key block cipher instead of a hash function.

**Reed-Solomon error correcting code implementation**

Homepage: https://github.com/cryodex/erc-js
(Languages: Javascript)

A Javascript implementation of Reed-Solomon error correcting codes. Reed-Solmon codes provide a systematic way of building codes that could detect and correct multiple random symbol errors.

**Paillier homomorphic encryption implementation**

Homepage: https://github.com/cryodex/hom-js
(Languages: Javascript)

 Javascript implementation of the Paillier cryptosystem, invented by Pascal Pailler in 1999. The Paillier cryptosystem is an additive homomorphic system, meaning that given the encryption of m1 and m2, one can compute the encryption of m1 + m2.

###Big Data

**Massively parallel watershed transform**

Homepage: https://github.com/louismullie/watershed-cuda
(Languages: CUDA C, Python)

A massively parallel implementation of the watershed transform, using MPI for distributing frames to a network of GPUs, and CUDA to perform the watershed transform directly inside the GPU.

**TF*IDF on Amazon Elastic MapReduce**

Homepage: https://github.com/louismullie/tf-idf-emr
(Languages: Python)

Python implementation of the TF*IDF algorithm on Amazon Elastic MapReduce, using MRJob. The TF*IDF algorithm is a numerical statistic that is intended to reflect how important a word is to a document in a collection or corpus.