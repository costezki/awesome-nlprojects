# Awesome NLP Projects
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> This is a curated list of projects directly connected or useful for Natural Language Processing (NLP)
which make a geek smile for they exist.
> Inspired by [Joseph Misiti's github project](https://github.com/josephmisiti/awesome-machine-learning#python)

Related Lists:

- [awesome-nlp](https://github.com/keon/awesome-nlp)
- [nlp-with-ruby](https://github.com/arbox/nlp-with-ruby)
- [awesome-community-curated-nlp](https://github.com/alvations/awesome-community-curated-nlp)
- [awesome-dl4nlp](https://github.com/brianspiering/awesome-dl4nlp)
- [awesome-d3](https://github.com/wbkd/awesome-d3)
- [awesome-python](https://github.com/vinta/awesome-python)
- [awesome-data-science-viz](https://github.com/quantmind/awesome-data-science-viz)
- [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning)
- [awesome-rl](https://github.com/aikorea/awesome-rl)
- [awesome-rnn](https://github.com/kjw0612/awesome-rnn)
- [awesome-public-datasets](https://github.com/ChristosChristofidis/awesome-public-datasets)

## Contents

- [Resources and Frameworks](#Resources-and-Frameworks)
- [Related Lists](#Other-Cool-stuff)
- [Deep Learning goodies](#Deep-Learning-Goodies)
- [Machine Learning](#Machine-learning)
- [Language modelling](#Language-modelling)
- [Other ML](#Other-ML)
- [Other Cool stuff](#another-section)
- [Contribute](#Contribute)
- [License](#License)
- [Dialogue frameworks](#Dialogue-frameworks)

## Periodic tables
- [Visualization](http://www.visual-literacy.org/periodic_table/periodic_table.html#)
- [Machine Learning](http://www.mln.io/resources/periodic-table/)

# Cheat Sheets
- [ML Cheat sheet](http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html)
- [Deep Learnign Cheat sheets](https://github.com/kailashahirwar/cheatsheets-ai)
- [Data Schience](https://startupsventurecapital.com/essential-cheat-sheets-for-machine-learning-and-deep-learning-researchers-efb6a8ebd2e5)
- [Deep Learning for NLP Best Practices](http://ruder.io/deep-learning-nlp-best-practices/)
- [Data Visualization Wikipedia](http://datavizproject.com/)

## Resources and Frameworks
- Apache NLPCraft - An API to convert natural language into actions [link](https://nlpcraft.apache.org)
- TRIPS
. Semantic Lexicon [link](http://www.cs.rochester.edu/research/trips/lexicon/browse-ont-lex-ajax.html)
. semantic parser [link](https://www.cs.rochester.edu/research/cisd/projects/trips/architecture/parser.html)
. [link] (http://trips.ihmc.us/parser/cgi/parse)
- C&C Boxer
. semantic parser [link](http://svn.ask.it.usyd.edu.au/trac/candc/wiki/Demo)
- EPILOG
. episodic logic framework [link](https://www.cs.rochester.edu/research/epilog/)
- KNEXT (the continuation of the Lore project)
. knowledge extraction into episodic logic (similar to babelnet) [link](http://cs.rochester.edu/research/lore/)
- FRED
. semantic parser/knowledge extractor [link](http://wit.istc.cnr.it/stlab-tools/fred)
. [link2](http://wit.istc.cnr.it/stlab-tools/fred/fredlib)
. related tools [link3](http://wit.istc.cnr.it/stlab-tools/)
- LEGALO is a novel Open Knowledge Extraction approach that performs unsupervised, open domain, and abstractive knowledge extraction from text for producing directly usable machine readable information. [link]()
- DELPH-IN
. Broader project for NLP; grammar, parser, [link](http://www.delph-in.net/erg/)
- LKB
. The LKB system is a grammar and lexicon development environment for use with unification-based linguistic formalisms. [link](http://moin.delph-in.net/LkbTop)
- Malt parser
. dependecy syntax parser [link](http://www.maltparser.org/)
- YAGO
. knowledge base [link](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/)
- GATE
. text engineering pipeline [link](https://gate.ac.uk/download/)
- Enju
. syntactic parser [link](http://kmcs.nii.ac.jp/~yusuke/enju/demo.html#10)
- Open NLP
. NLP framework in Java [link](http://opennlp.apache.org/)
- CoreNLP
. stanford core NLP framework for parsing [link](http://stanfordnlp.github.io/CoreNLP/)
- NLTK
. awersome NLP framework in Python [link](nltk.org)
- PyNLPL
. Python library for Natural Language Processing. It contains various modules useful for common, and less common, NLP tasks. [link](https://github.com/CLARIAH/wp3-pynlpl)
- Valex
. Categorization of English Verbs [link](http://ilexir.co.uk/applications/valex/)
- Unified verb Index
. VerbNet and FrameNEt togetehr [link](http://verbs.colorado.edu/verb-index/)
- scikit-learn
. Machine learning in Python. Simple and efficient tools for data mining and data analysis [link](http://scikit-learn.org/stable/)
- Tuffy
. Scalable Markov Logic inference engine [link](http://i.stanford.edu/hazy/tuffy/)
- Fexlix
. the successor of Tuffy [link](http://i.stanford.edu/hazy/felix/doc/)
- Alchemy
. algorithms for statistical relational learning and probabilistic logic inference, based on the Markov logic representation [link](http://alchemy.cs.washington.edu/)
- pracmln
. Marcov Logic in Python, this project started as a fork to ProbCong project. Find more [link](http://www.pracmln.org/)
- ProbCog
. ProbCog is a statistical relational learning and reasoning system that supports efficient learning and inference in relational domains	[link](https://github.com/opcode81/ProbCog/wiki)
- KReator
. KReator is an integrated development environment (IDE) for relational probabilistic knowledge representation languages. At the moment, KReator supports Bayesian Logic Programs (BLPs), Markov Logic Networks (MLNs), Relational Maximum Entropy (RME), Relational Bayesian Networks (RBN), and Probabilistic Prolog (ProbLog). [link](http://kreator-ide.sourceforge.net/)
- pyHTM
. pyHTM - Hierarchical Temporal Memory in Python;
. Our machine intelligence technology is called Hierarchical Temporal Memory (HTM), which is a detailed computational theory of the neocortex. At the core of HTM are time-based learning algorithms that store and recall spatial and temporal patterns. HTM is well suited to a wide variety of problems, particularly those with the following characteristics:
.   Streaming data rather than static databases
.    Underlying patterns in the data change over time
.    Many individual data sources where hand crafting separate models is impractical
.    Subtle patterns that can’t always be seen by humans
.    Time-based patterns
.    Simple techniques such as thresholds yield substantial false positives and false negatives
. [link]	(https://github.com/carver/pyHTM)
- KnowRob
. KnowRob is a knowledge processing system that combines knowledge representation and reasoning methods with techniques for acquiring knowledge and for grounding the knowledge in a physical system and can serve as a common semantic framework for integrating information from different sources. KnowRob combines static encyclopedic knowledge, common-sense knowledge, task descriptions, environment models, object information and information about observed actions that has been acquired from various sources (manually axiomatized, derived from observations, or imported from the web). It supports different deterministic and probabilistic reasoning mechanisms, clustering, classification and segmentation methods, and includes query interfaces as well as visualization tools. [link](https://github.com/knowrob/knowrob)
- GHMM
. The General Hidden Markov Model library (GHMM) is a freely available C library implementing efficient data structures and algorithms for basic and extended HMMs with discrete and continous emissions. It comes with Python wrappers which provide a much nicer interface and added functionality.	[link](http://ghmm.org/)
. pyHSMM	"This is a Python library for approximate unsupervised inference in Bayesian Hidden Markov Models (HMMs) and explicit-duration Hidden semi-Markov Models (HSMMs), focusing on the Bayesian Nonparametric extensions, the HDP-HMM and HDP-HSMM, mostly with weak-limit approximations. There are also some extensions:
. autoregressive models
. switching linear dynamical systems
. factorial models
. [link](https://github.com/mattjj/pyhsmm)
- Prism
. symbolic-statistical models; a model checker for temporal logic and quantitative extensions; verification for realtime systems; markov models etc.
. [link](http://www.prismmodelchecker.org/doc/)
- UBY
. A Large-Scale Unified Lexical-Semantic Resource [link](https://www.ukp.tu-darmstadt.de/data/lexical-resources/uby/)
- Duckling
. probabilistic CFG parser for dimensions (time, temperature, size etc) [link](https://duckling.wit.ai/)
- SLING - A natural language frame semantics parser 
. semantic parser implemented using deep Recurrent Neural Network [link](https://github.com/google/sling)
- Wit
. intent parser [link](https://wit.ai/)
- Mycroft
. a company making another intent parser, a Speech2Text and a Text2Speech frameworks in Python [link](https://mycroft.ai/projects/)
- IEPY
. IEPY is an open source tool for Information Extraction focused on Relation Extraction.[link](https://github.com/machinalis/iepy)
- MITIE
. This project provides free (even for commercial use) state-of-the-art information extraction tools. The current release includes tools for performing named entity extraction and binary relation detection as well as tools for training custom extractors and relation detectors. [link](https://github.com/mit-nlp/MITIE)
- SyntaxNet
. an open-source neural network framework for TensorFlow that provides a foundation for Natural Language Understanding (NLU) systems. Our release includes all the code needed to train new SyntaxNet models on your own data, as well as Parsey McParseface, an English parser that we have trained for you, and that you can use to analyze English text. [link](https://github.com/tensorflow/models/tree/master/syntaxnet)
- OpenAI Gym
. A toolkit for developing and comparing reinforcement learning algorithms. [link](https://github.com/openai/gym)
- spiff workflow
. Spiff Workflow is a library implementing a framework for workflows. It is based on http://www.workflowpatterns.com and implemented in pure Python. [link](https://github.com/knipknap/SpiffWorkflow) [Workflow patterns] (http://www.workflowpatterns.com/) The aim of this initiative is to provide a conceptual basis for process technology. In particular, the research provides a thorough examination of the various perspectives (control flow, data, resource, and exception handling) that need to be supported by a workflow language or a business process modelling language.
- A news reader project
. [link](newsreader-project.eu)
- word sense disambiguation toolkit in python using word2vec (contains datasets too) [link](https://github.com/tudarmstadt-lt/sensegram)
- annotated document server for FOLIA format [link](https://github.com/proycon/foliadocserve) 
- toolkit useful for working with corpus annotations in FOLIA and other formats (compare to Dan's corpkit) [link](https://github.com/proycon/pynlpl)
- vaderSentiment 
Sentiment analysis tool for Python [link](https://github.com/cjhutto/vaderSentiment)
- Wowpal Wabbit - a reinformecement learning setup using structured prediction technique [link](https://github.com/JohnLangford/vowpal_wabbit) 
. Vowpal Wabbit is a machine learning system which pushes the frontier of machine learning with techniques such as online, hashing, allreduce, reductions, learning2search, active, and interactive learning. [link](http://hunch.net/~vw/)
- TiMBL - an open source software package implementing several memory-based learning algorithms, among which IB1-IG, an implementation of k-nearest neighbor classification with feature weighting suitable for symbolic feature spaces, and IGTree, a decision-tree approximation of IB1-IG. [link](https://languagemachines.github.io/timbl/) [link1](https://github.com/LanguageMachines/timbl/) [link3]()
- PIKES - knowledge extraction suite [link](https://github.com/dkmfbk/pikes) [link](http://pikes.fbk.eu/eval-pm.html)
- RDFPro - the swiss knowfe ro RDF manipulation, stream base RDF processing [link](http://rdfpro.fbk.eu/)
- spacy - Industrial-strength Natural Language Processing (NLP) with Python and Cython [link](https://github.com/explosion/spaCy)
- textacy - Higher level NLP built on spaCy [link](https://github.com/chartbeat-labs/textacy)
- Ukb - graph-based WSD and similarity [link](https://github.com/asoroa/ukb)
- marseille - Mining Argument Structures with Expressive Inference (Linear and LSTM Engines) [link](https://github.com/vene/marseille)
- Fluid construction grammar - [link](https://www.fcg-net.org/contact-us/)
- Python cognitive modelling suite - [link](https://github.com/tcstewar/ccmsuite)
- Rasa - Natural language understanding [link](https://github.com/RasaHQ/rasa_nlu)
- SenticNet - Talking about SenticNet is talking about concept-level sentiment analysis, that is, performing tasks such as polarity detection and emotion recognition by leveraging on semantics and linguistics in stead of solely relying on word co-occurrence frequencies. [link](http://sentic.net/about/) [link](https://github.com/SenticNet)
- Explore NLP - [link](https://kandi.openweaver.com/explore/nlp)

## Deep Learning goodies
* Neural Storry teller [code](https://github.com/ryankiros/neural-storyteller)
* open type entity recognition system [code](https://github.com/openai/deeptype)

## Resources
- BabelNet - Multilingual Enciclopedic Dictionnary [link](http://babelnet.org/download)
- Nasari - semantic vector representation for BabelNet [link](http://lcl.uniroma1.it/nasari/)

## Language modelling
* Adaptive Skip-gram implementation in Julia [link](https://github.com/sbos/AdaGram.jl)
* Skip Sentence encoder [code](https://github.com/ryankiros/skip-thoughts), [paper](https://arxiv.org/abs/1506.06726)
* Attentive reader [code](https://github.com/caglar/Attentive_reader), [paper](https://arxiv.org/pdf/1506.03340v3)
* GenSim - topic modelling library for python, also includes a vord2vec implementation [link](http://radimrehurek.com/gensim/index.html)
* vord2vec - Original C implementation and some precomputed resources [link](https://code.google.com/archive/p/word2vec/)
* Skip Sentence encoder [code](https://github.com/ryankiros/skip-thoughts), [paper](https://arxiv.org/abs/1506.06726)
* Attentive reader [code](https://github.com/caglar/Attentive_reader), [paper](https://arxiv.org/pdf/1506.03340v3)
* FastText - Faster, better text classification, Library for fast text representation and classification. [link](https://github.com/facebookresearch/fastText)
* InferSent - Sentence embeddings (InferSent) and training code for NLI [link](https://github.com/facebookresearch/InferSent)

## Other ML
* deep learning platform MxNet + NuymPy [code]( https://github.com/dmlc/minpy)


## Other Cool stuff
- Node Box
. NodeBox makes it easy to do data visualisations, generative design and complex production challenges. [link](https://www.nodebox.net/node/)
- Callimacus - Linked open data, RDF, web application, data visualization etc. [link](http://callimachusproject.org/)
- Feature Forge
. This library provides a set of tools that can be useful in many machine learning applications (classification, clustering, regression, etc.), and particularly helpful if you use scikit-learn (although this can work if you have a different algorithm). [link][https://github.com/machinalis/featureforge/tree/master]
- Storry generator algorithms
. [link][http://wikis.sub.uni-hamburg.de/lhn/index.php/Story_Generator_Algorithms]
- OpenCog AI framework
OpenCog is an open-source software project aimed at directly confronting the Artificial General Intelligence (AGI) challenge, using mathematical and biological inspiration and professional software engineering techniques.
. [link](https://github.com/opencog/opencog)
- FoLiA Linguistic Annotation Tool [link](https://github.com/proycon/flat)
- WebAnno - a linguistic annotation tool [link](https://webanno.github.io/webanno/)
- Visdom - A flexible tool for creating, organizing, and sharing visualizations of live, rich data. [link](https://github.com/facebookresearch/visdom)


## Dialogue frameworks
- [Chat script](https://github.com/bwilcox-1234/ChatScript) - Natural Language tool/dialog manager - [link1](https://sourceforge.net/projects/chatscript/), [link2](https://github.com/bwilcox-1234/ChatScript), 
- [Chatter bot](http://chatterbot.readthedocs.io/en/stable/#) - ChatterBot is a Python library that makes it easy to generate automated responses to a user’s input. ChatterBot uses a selection of machine learning algorithms to produce different types of responses.
- [RiveScript](https://www.rivescript.com/about) - RiveScript is a simple scripting language for chatbots with a friendly, easy to learn syntax.
Create your own chatbot in Go, Java, JavaScript, Perl or Python.
- [SuperScript](http://superscriptjs.com/) - A dialog system and bot engine for conversational UI's.
- [BotKit](https://github.com/howdyai/botkit) - Botkit is designed to ease the process of designing and running useful, creative bots that live inside messaging platforms. 


## Similar lists
- [awesome nlp](https://github.com/keon/awesome-nlp)
- [awesome dl nlp](https://github.com/brianspiering/awesome-dl4nlp)
- Rochester University project list
. potentially useful links
. [link](https://www.cs.rochester.edu/research/cisd/projects/)
- Misiti's list
. [link](https://github.com/josephmisiti/awesome-machine-learning#python)
- Description Logic reasoners
. list of reasoners [link](http://owl.cs.manchester.ac.uk/tools/list-of-reasoners/)
- Illinois Projects	List
. of software from Illinois Cognitive Computation Group	[link](https://cogcomp.cs.illinois.edu/page/software/)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Eugeniu Costezki has waived all copyright and
related or neighboring rights to this work.
