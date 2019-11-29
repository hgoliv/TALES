# PT Lexical Semantics

This repository includes different computational resources around lexical-semantic knowledge in Portuguese and can be seen as a follow-up to the Onto.PT and CONTO.PT projects (http://ontopt.dei.uc.pt/).

The following resources are included:

* Large Portuguese Lexical-Semantic Knowledge Base (LKB), with instances of lexical-semantic relations acquired from ten computational lexical resources: PAPEL, Dicionário Aberto, Wikcionário.PT, TeP, OpenThesaurus.PT, OpenWordNet-PT, PULO, Port4Nooj, Wordnet.Br, ConceptNet.

* PT-LKB embeddings, word embeddings learned from the structure of the large Portuguese LKB with node2vec.

* TALES, acronym for the Portuguese name "Teste de Analogias LÉxico-Semânticas", is an analogy-like test with lexical-semantic relations for assessing Portuguese word embeddings.
It is organised similarly to the Bigger Analogy Test Set (BATS, http://vecto.space/data/).
It includes several files, each targeting a different relation, with 50 "questions" in each. Here, a question correspondents to the first argument of a relation a, followed by possible second arguments a', split by /.
Instances of lexical-semantic relations were acquired from the large Portuguese LKB.
