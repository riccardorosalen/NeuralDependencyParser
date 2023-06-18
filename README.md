# NeuralDependencyParser
Dependency Parsing with ArcEager Parser and Neural Networks

The notebook implements a parser and an oracle that use the ArcEager strategy to perform dependency parsing.
Then uses a transformer Neural Network (BERT or BiLSTM) to encode sentences' words. 
Finally a MLP is trained to perform parsing following the Oracle and the Parser.

The code has been realized to fit the Universal Dependencies dataset, in particular it also filters the sentences if a dataset has None indices.

Notebook fully implemented with Google Colab.


