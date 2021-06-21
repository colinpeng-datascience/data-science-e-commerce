# Data_Science_with_Ecommerce
This repository contains some sample codes of my work as a data scientist in an ecommerce company.

In model_verify_pair.ipynb, the notebook contains a model I made from scratch to evaluate if a keyword(a short sentence or a word) and a sentence( a long sentence or a paragraph) is a match. I used two encoder RNNs, one for the keyword and one for the description, plus a Attention-like mechanism that concates the encoded keyword to every word of the sentence to make sure our model remember the keyword when reading the sentence.

In model_keyword_extract.ipynb, the notebook contains a model I made to do keyword-extraction using Seq2Seq neural network with Attention mechanism.

For more information, please click into the file or contacts colin100113@gmail.com
