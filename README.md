# Autcompletion Task
This repository contains a notebook for training RNN on a 3-character autocompeltion task.

## Assessment Brief:

Humans can complete words, sentences (and even sounds) when parts were lost or were 
masked by noise. Likewise, text-editing programmes can make suggestions for the text that 
follows. This is what you will be doing in this task: 
Use deep learning to build a model that predicts the next three characters (e.g., “Merry 
Christ…” -> “mas”). Evaluate the training and performance of the model. Present the code in 
a manner that makes it easy to use for others. In your discussion, comment on why you 
chose your model and parameters. A good discussion presents further architectures and 
why you did not choose them. If the model does not perform well, explain what would be 
needed to improve it. Marking (see below) will be based on the design, implementation and 
evaluation of the deep learning approach, not necessarily on the accuracy achieved. 
For your database, you can choose or combine from any of the ebooks that are uploaded to 
Moodle in the assignment section. Your model must not have used any other data. It is your 
task to create appropriate training and test sets from the data provided.

## Overview
This project demonstrates how to:

* Load and preprocess the seven assigned books from Project Gutenberg.
* Creating and training an LSTM to perform the 3-character prediction task.
* Implement a custom `Dataset` class for efficient data loading and batching.
* Create a `Trainer` class for streamlined training and evaluation.
* Evaluate the selection of hyperparameters to demonstrate in-depth knowledge and understanding of NLP and deep learning.

## License 

This repository is licensed under the MIT License. See the LICENSE file for details.

---

Happy coding! ✨🐇

