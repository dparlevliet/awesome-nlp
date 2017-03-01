Speech and Natural Language Processing
======================================

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of speech and natural language processing resources.
Other lists can be found in this [list](https://github.com/bayandin/awesome-awesomeness). If you want to contribute to this list (please do), send me a pull request.


Table of Contents
-----------------

-   [SaaS](#saas-apis)
  -     [NLP](#nlp-saas)
-   [Finite State Toolkits and Regular Expressions](#finite-state-toolkits-and-regular-expressions)
-   [Language Modelling Toolkits](#language-modelling-toolkits)
-   [Speech Recognition](#speech-recognition)
-   [Signal Processing](#signal-processing)
-   [Text-to-Speech](#text-to-speech)
-   [Speech Data](#speech-data)
-   [Machine Translation](#machine-translation)
-   [Machine Learning](#machine-learning)
-   [Deep Learning](#deep-learning)
-   [Natural Language Processing](#natural-language-processing)
-   [Applications](#applications)
-   [Other Tools](#other-tools)
-   [Blogs](#blogs)
-   [Books](#books)


SaaS Apis
---------

**[`^        back to top        ^`](#)**

### NLP SaaS
-   [Google Cloud Natural Language API](https://cloud.google.com/natural-language/)
-   [IBM Watson Alchemy Language](https://www.ibm.com/watson/developercloud/alchemy-language.html)
-   [Microsoft Cognitive Service](https://www.microsoft.com/cognitive-services/en-us/text-analytics-api)
-   [Aylien](https://developer.aylien.com/text-api-demo)
-   [Indico](https://www.indico.io)
-   [TextRazor](https://www.textrazor.com)
-   [MeaningCloud](https://www.meaningcloud.com)
-   [Rosette](https://www.rosette.com)


Finite State Toolkits and Regular Expressions
---------------------------------------------

**[`^        back to top        ^`](#)**

-   [Carmel](https://github.com/graehl/carmel) Finite-state toolkit, EM and Bayesian (Gibbs sampling) training for FST and context-free derivation forests/
-   [Categorial semiring](http://openfst.org/twiki/pub/Contrib/FstContrib/categorial-1.3.3.tar.gz) Categorial semiring as described in [Sproat et al. 2014](http://www.mitpressjournals.org/doi/pdf/10.1162/COLI_a_00198)
-   [dk.brics.automaton](http://www.brics.dk/automaton/) Java toolkit for FSAs and regular expression.
-   [Fare](https://github.com/moodmosaic/Fare) Fare is a finite state and regular expression libary for the .NET framework written in C\#. am is a JavaScript library for working with automata and formal grammars for regular and context-free languages
-   [Foma](https://github.com/mhulden/foma) Finite-state compiler and C library
-   [fsm2.0](http://tagh.de/tom/wp-content/uploads/fsm-12.6.2012.zip) Thomas Hanneforths fsm 2.0 library written C++ has a few nice operations such as three-way composition
-   [fstrain](https://github.com/markusdr/fstrain) A toolkit for training finite-state models
-   [jopenfst](https://github.com/steveash/jopenfst) Java port of the C++ OpenFst library; originally forked from the CMU Sphinx project
-   [Kleene programming language](https://github.com/krbeesley/kleene-lang) High level finite state programming language built on top of OpenFst.
-   [MIT FST Toolkit](http://people.csail.mit.edu/ilh/fst/) WFST toolkit no maintained anymore but feature a few commands not found in other toolkits
-   [MoMs-for-StochasticLanguages](https://github.com/ICML14MoMCompare/MoMs-for-StochasticLanguages) Spectral and other training algorithms for WFSAs.
-   [n Shortest Path for PDT](https://github.com/kho/openfst) n Shortest Path for PDT
-   [Noam](https://github.com/izuzak/noam) "Noam is a JavaScript library for working with automata and formal grammars for regular and context-free languages". Also has pretty cool examples using
-   [viz.js](https://github.com/mdaines/viz.js/)
-   [OpenFst](http://openfst.org) OpenFst is a library for constructing, combining, optimizing, and searching weighted finite-state transducers (FSTs).
-   [openfst-utils](https://github.com/benob/openfst-utils) Nice set of utilities for OpenFst includes implementation of Categorial semirings.openfst-utils.
-   [openlat](https://github.com/benob/openlat) Toolkit for manipulating word lattice built on top of OpenFst. Includes support for reading and writing HTK compatible lattices.
-   [PyFst](https://github.com/vchahun/pyfst) Python interface to OpenFst
-   [SFST - Stuttgart Finite State Transducer Tools](http://www.ims.uni-stuttgart.de/tcl/SOFTWARE/SFST.html) "SFST is a toolbox for the implementation of morphological analysers and other tools which are based on finite state transducer technology."
-   [Treba](https://code.google.com/p/treba/) "Treba is a basic command-line tool for training, decoding, and calculating with weighted (probabilistic) finite state automata (PFSA) and Hidden Markov Models (HMMs)."

Many of the tools in the machine translation section also implement
interesting graph and semiring operations.


Language Modelling Toolkits
---------------------------

**[`^        back to top        ^`](#)**

-   [Bayesian Recurrent Neural Network for Language Modeling](http://chien.cm.nctu.edu.tw/bayesian-recurrent-neural-network-for-language-modeling/) This is a C/C++ implementation for Bayesian recurrent neural network for language modeling (BRNNLM)
-   [Berkeley LM](http://code.google.com/p/berkeleylm/)
-   [Bigfatlm](https://github.com/jhclark/bigfatlm) Provides Hadoop training of Kneser-ney language models, written in Java.
-   [CSLM](http://www-lium.univ-lemans.fr/cslm/) "Continuous Space Language Model toolkit. CSLM toolkit is open-source software which implements the so-called continuous space language model.
-   [DALM](https://github.com/jnory/DALM) Double array language model.
-   [KenLM](http://kheafield.com/code/kenlm/) Kenneth Heafield's language model toolkit, uses a very fast and low memory representation.
-   [lwlm](http://chasen.org/~daiti-m/dist/lwlm/) lwlm is an exact, full Bayesian implementation of the Latent Words Language Model (Deschacht and Moens, 2009).
-   [Maximum Entropy Modeling](http://homepages.inf.ed.ac.uk/lzhang10/maxent.html) Le Zhang has a comprehensive set of links related MaxEnt models.
-   [Maximum entropy language models: SRILM extension](http://www.phon.ioc.ee/dokuwiki/doku.php?id=people:tanel:srilm-me.en) "This patch adds the functionality to train and apply maximum entropy (MaxEnt) language models to the SRILM toolkit. Currently, only N-gram features are supported"
-   [mitlm](https://code.google.com/p/mitlm/) My personal favourite LM toolkit, super fast and seems to get slightly higher accuracy.
-   [MSRLM](http://research.microsoft.com/en-us/downloads/78e26f9c-fc9a-44bb-80a7-69324c62df8c/default.aspx) "This scalable language-model tool is used to build language models from large amounts of data. It supports modified absolute discounting and Kneser-Ney smoothing."
-   [OpenGrm](http://opengrm.org) Language modelling toolkit for use with OpenFst.
-   [cpyp](https://github.com/redpony/cpyp) C++ library for modeling with Pitman-Yor processes
-   [RandLM](http://sourceforge.net/projects/randlm/) Bloom filter based random language models
-   [RNNLM](http://www.fit.vutbr.cz/~imikolov/rnnlm/) Recurrent neural network language model toolkit.
-   [Refr](http://code.google.com/p/refr) Re-ranking framework from the Johns-Hopkins workshop on confusion language modelling.
-   [rwthlm](http://www-i6.informatik.rwth-aachen.de/web/Software/rwthlm.php) A toolkit for training neural network language models (feedforward, recurrent, and long short-term memory neural networks). The software was written by Martin Sundermeyer.
-   [SRILM](http://www.speech.sri.com/projects/%20srilm/) Very popular toolkit, source code avaliable but only non-free for commerical use.


Speech Recognition
------------------

**[`^        back to top        ^`](#)**

-   [AaltoASR](https://github.com/aalto-speech) Aalto Automatic Speech Recognition tools
-   [Barista](https://github.com/usc-sail/barista) Barista is an open-source framework for concurrent speech processing.
-   [Bavieca](http://www.bavieca.org/index.html) New open source toolkit featuring static and dynamic decoders.
-   [kaldi-nnet-dur-model](https://github.com/alumae/kaldi-nnet-dur-model) Neural network phone duration model on top of the Kaldi speech recognition framework, [(Interspeech paper)](https://phon.ioc.ee/dokuwiki/lib/exe/fetch.php?media=people:tanel:icassp2014-durmodel.pdf)
-   [CMU Sphinx](http://cmusphinx.sourceforge.net/) Open Source Toolkit For Speech Recognition Project by Carnegie Mellon University
-   [HTK](http://htk.eng.cam.ac.uk/) "The Hidden Markov Model Toolkit (HTK) is a portable toolkit for building and manipulating hidden Markov models."
-   [Juicer](https://github.com/idiap/juicer) Juicer is a Weighted Finite State Transducer (WFST) based decoder for Automatic Speech Recognition (ASR).
-   [Julius](http://julius.sourceforge.jp/en_index.php) "Julius is a high-performance, two-pass large vocabulary continuous speech recognition (LVCSR) decoder software for speech-related researchers and developers."
-   [Kaldi](http://kaldi.sourceforge.net/) Modern open source toolkit lead by Dan Povey featuring many state-of-the-art techniques.
-   [OpenDcd](http://opendcd.org/) An Open Source WFST based Speech Recognition Decoder.
-   [Phonetisaurus](https://code.google.com/p/phonetisaurus/) Josef Novak's super fast WFST based Phoneticizer, site also has some really nice tutorials slides.
-   [Sail Align](https://github.com/nassosoassos/sail_align) SailAlign is an open-source software toolkit for robust long speech-text alignment implementing an adaptive, iterative speech recognition and text alignment scheme that allows for the processing of very long (and possibly noisy) audio and is robust to transcription errors. It is mainly written as a perl library but its functionality also depends...
-   [SCARF: A Segmental CRF Toolkit for Speech Recognition](http://research.microsoft.com/en-us/projects/scarf/) "SCARF is a toolkit for doing speech recognition with segmental conditional random fields."
-   [trainc](https://code.google.com/p/trainc/) David Rybach and Michael Riley's tool for direct construction of context-dependency transducers (Interspeech best paper).
-   [RASR](http://www-i6.informatik.rwth-aachen.de/rwth-asr/) RWTH ASR -The RWTH Aachen University Speech Recognition System


Signal Processing
-----------------

**[`^        back to top        ^`](#)**

-   [An Interactive Source Separation Editor](http://isse.sourceforge.net/) "ISSE is an open-source, freely available, cross-platform audio editing tool that allows a user to perform source separation by painting on time-frequency visualisations of sound."
-   [Bob](https://github.com/idiap/bob) Bob is a free signal-processing and machine learning toolbox originally developed by the Biometrics group at Idiap Research Institute, in Switzerland.
-   [Matlab Audio Processing Examples](http://www.ee.columbia.edu/~dpwe/resources/matlab/)
-   [SAcC - Subband Autocorrelation Classification Pitch Tracker](http://labrosa.ee.columbia.edu/projects/SAcC/) "SAcC is a (compiled) Matlab script that performs noise- robust pitch tracking by classifying the autocorrelations of a set of subbands using an MLP neural network."


Text-to-Speech
--------------

**[`^        back to top        ^`](#)**

-   [HTS](http://hts.sp.nitech.ac.jp/) HMM-based speech synthesis
-   [RusPhonetizer](https://github.com/wilpert/RusPhonetizer) Grammar rules and dictionaries for the phonetic transcription of Russian sentences


Speech Data
-----------

**[`^        back to top        ^`](#)**

-   [cmudict](https://github.com/cmusphinx/cmudict) CMUdict (the Carnegie Mellon Pronouncing Dictionary) is a free pronouncing dictionary of English.
-   [LibriSpeech ASR corpus](http://www.openslr.org/12/) LibriSpeech is a corpus of approximately 1000 hours of 16kHz read English speech, prepared by Vassil Panayotov with the assistance of Daniel Povey. The data is derived from read audiobooks from the LibriVox project, and has been carefully segmented and aligned.
-   [TED-LIUM Corpus](http://www-lium.univ-lemans.fr/en/content/ted-lium-corpus) The TED-LIUM corpus was made from audio talks and their transcriptions available on the TED website.


Machine Translation
-------------------

**[`^        back to top        ^`](#)**

-   [Berkeley Aligner](https://code.google.com/p/berkeleyaligner/) "...a word alignment software package that implements recent innovations in unsupervised word alignment."
-   [cdec](https://github.com/redpony/cdec) "Decoder, aligner, and model optimizer for statistical machine translation and other structured prediction models based on (mostly) context-free formalisms"
-   [Jane](http://www-i6.informatik.rwth-aachen.de/jane/) "Jane is RWTH's open source statistical machine translation toolkit. Jane supports state-of-the-art techniques for phrase-based and hierarchical phrase-based machine translation."
-   [Joshua](http://joshua-decoder.org/) Hierarchical and syntax based machine translation decoder written in Java.
-   [Moses](http://www.statmt.org/moses/) Standard open source machine translation toolkit.
-   [alignment-with-openfst](https://github.com/ldmt-muri/alignment-with-openfst)
-   [zmert](http://cs.jhu.edu/~ozaidan/zmert/) Nice Java Mert implementation by [Omar F. Zaidan](http://www.cs.jhu.edu/~ozaidan/)


Machine Learning
----------------

**[`^        back to top        ^`](#)**

-   [BIDData](https://github.com/BIDData) BIDMat is a matrix library intended to support large-scale exploratory data analysis. Its sister library BIDMach implements the machine learning layer.
-   [libFM: Factorization Machine Library](http://libfm.org/)
-   [sofia-ml](https://code.google.com/p/sofia-ml/) Fast incremental learning algorithms for classification, regression, ranking from Google.
-   [Spearmint](https://github.com/JasperSnoek/spearmint) Spearmint is a package to perform Bayesian optimization according to the algorithms outlined in the paper: Practical Bayesian Optimization of Machine Learning Algorithms Jasper Snoek, Hugo Larochelle and Ryan P. Adams Advances in Neural Information Processing Systems, 2012


Deep Learning
-------------

**[`^        back to top        ^`](#)**

-   [Benchmarks](https://github.com/soumith/convnet-benchmarks) - Comparison of different convolution network implementations.
-   [Cafee](http://arxiv.org/pdf/1409.3215v1.pdf) - Really active deep learning toolkit with support for cuDNN and lots of other backends.
-   [cuDNN](https://developer.nvidia.com/cudnn) - Deep neural network from Nvidia with paper [here](http://arxiv.org/pdf/1410.0759.pdf). [Torch 7 has support for cuDnn](https://github.com/soumith/cudnn.torch) and [here](https://github.com/hannes-brt/cudnn-python-wrappers) are some Python wrappers.
-   [CURRENNT](http://sourceforge.net/projects/currennt/) - Munich Open-Source CUDA RecurREnt Neural Network Toolkit described in this [paper](http://www.mmk.ei.tum.de/publ/pdf/14/14wen7.pdf)
-   [gensim](http://radimrehurek.com/gensim/index.html) - Python topic modeling toolkit with word2vec implementation. Extremly easy to use and to install.
-   [Glove](http://www.socher.org/index.php/Main/GloveGlobalVectorsForWordRepresentation) Global vectors for word representation.
-   [GroundHog](https://github.com/lisa-groundhog/GroundHog) Neural network based machine translation toolkit.
-   [KALDI LSTM](https://github.com/dophist/kaldi-lstm) C++ implementation of LSTM (Long Short Term Memory), in Kaldi's nnet1 framework. Used for automatic speech recognition, possibly language modeling etc.
-   [OxLM: Oxford Neural Language Modelling Toolkit](https://github.com/pauldb89/OxLM) Neural network toolkit for machine translation described in the paper [here](https://ufal.mff.cuni.cz/pbml/102/art-baltescu-blunsom-hoang.pdf)
-   [Neural Probabilistic Language Model Toolkit](http://nlg.isi.edu/software/nplm/) "NPLM is a toolkit for training and using feedforward neural language models (Bengio, 2003). It is fast even for large vocabularies (100k or more): a model can be trained on a billion words of data in about a week, and can be queried in about 40 μs, which is usable inside a decoder for machine translation."
-   [RNNLM2WFST](https://github.com/glecorve/rnnlm2wfst) Tool to convert RNNLMs to WFSTs
-   [ViennaCL](http://viennacl.sourceforge.net) ViennaCL is a free open-source linear algebra library for computations on many-core architectures (GPUs, MIC) and multi-core CPUs.


Natural Language Processing
---------------------------

**[`^        back to top        ^`](#)**

-   [BLLIP reranking parser](https://github.com/BLLIP/bllip-parser) "BLLIP Parser is a statistical natural language parser including a generative constituent parser (first-stage) and discriminative maximum entropy reranker (second-stage)."
-   [OpenNLP](http://opennlp.apache.org/) The Apache OpenNLP library is a machine learning based toolkit for the processing of natural language text.
-   [SEAL](https://github.com/TeamCohen/SEAL) Set expander for any language described in this [paper](http://www.cs.cmu.edu/~wcohen/postscript/icdm-2007.pdf)
-   [Stanford CoreNLP](http://nlp.stanford.edu/software/corenlp.shtml) "Stanford CoreNLP provides a set of natural language analysis tools written in Java"
-   [SPLAT](https://github.com/meyersbs/SPLAT) "SPLAT, the Speech Processing & Linguistic Analysis Tool is an open source Python3.4 library and command line tool designed to be intuitive, efficient, and fast. Given a text, SPLAT can calculate a variety of metrics to help you with your research!"


Applications
------------

**[`^        back to top        ^`](#)**

-   [Cloud ASR using PyKaldi](https://github.com/UFAL-DSG/cloud-asr) "CloudASR is a software platform and a public ASR webservice."


Other Tools
-----------

**[`^        back to top        ^`](#)**

-   [GraphViz.sty](https://github.com/mprentice/GraphViz-sty) Really handy tool adding dot languge directly to a LaTex document, useful for tweaking the small colorized WFST figure in papers and presentations.


Blogs
-----

**[`^        back to top        ^`](#)**

-   [Between One and Zero](http://williamhartmann.wordpress.com/) by William Hartmann
-   [cmusphinx](http://cmusphinx.sourceforge.net/) CMU Sphinx related blog
-   [Language Log](http://languagelog.ldc.upenn.edu/nll/)
-   [LingPipe Blog](http://lingpipe-blog.com/) Natural Language Processing and Text Analytics
-   [Natural Language Processing Blog](http://nlpers.blogspot.ch/) by Hal Daumé III
-   [Spoken Language Processing](http://spokenlanguageprocessing.blogspot.jp/) "Some thoughts on Spoken Language Processing, with tangents on Natural Language Processing, Machine Learning, and Signal Processing thrown in for good measure."


Books
-----

**[`^        back to top        ^`](#)**

-   [DEEP LEARNING: Methods and Applications](http://research.microsoft.com/pubs/209355/DeepLearning-NowPublishing-Vol7-SIG-039.pdf) By Li Deng and Dong Yu
-   [Foundations of Data Science](http://www.cs.cornell.edu/jeh/NOSOLUTIONS90413.pdf) Draft by John Hopcroft and Ravindran Kannan
-   [Introduction to Matrix Methods and Applications](http://stanford.edu/class/ee103/mma.pdf) (Working Title) S. Boyd and L. Vandenberghe

