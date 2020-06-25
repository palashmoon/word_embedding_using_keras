# Implementing Word Embedding Using Keras

## Word Embedding:
A word embedding is a learned representation for text where words that have the same meaning have a similar representation.</br>
Word embeddings are in fact a class of techniques where individual words are represented as real-valued vectors in a predefined vector space. Each word is mapped to one vector and the vector values are learned in a way that resembles a neural network, and hence the technique is often lumped into the field of deep learning.</br>
Key to the approach is the idea of using a dense distributed representation for each word.

Each word is represented by a real-valued vector, often tens or hundreds of dimensions. This is contrasted to the thousands or millions of dimensions required for sparse word representations, such as a one-hot encoding.</br>

The distributed representation is learned based on the usage of words. This allows words that are used in similar ways to result in having similar representations, naturally capturing their meaning.</br>

## Prerequisite:
if you are using Anacaonda promt then create new Environment using (conda create -n myenv python=3.6) then follw the following commands.</br>
 1. Tensorflow 2.2 (pip install tensorflow==2.2) </br>
 2. keras (pip install keras) </br>
 Or </br>
 pip install -r requirement.txt (this will download all the dependencies).</br>
