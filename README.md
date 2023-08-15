# Word analogy prediction using Skipgram and CBOW

This repository contains a Python implementation of the Skip-gram and CBOW word embedding models from scratch. Skip-gram and CBOW are popular algorithms used for learning word representations in natural language processing.

## Contributors

- Akshay Eknath Mali 
- Mahesh Abnave
- Sanjana Mohan
- Meet Joshi



## Table of Contents

- [Introduction](#introduction)
- [Implementation Details](#implementation-details)

## Introduction

Word embeddings are essential in many NLP tasks as they capture semantic relationships between words in a continuous vector space. Skip-gram and CBOW are two fundamental techniques to create word embeddings. Skipgram aims to predict context words given a target word, while CBOW predicts the target word based on its context words.

This project demonstrates the step-by-step implementation of Skipgram and CBOW models using Python and NumPy.

## packages
- Python (>= 3.6)
- NumPy (>= 1.19)

## Implementation Details

- The implementation follows the skip-gram and CBOW architectures as described in the original papers.
- The training process involves creating a dataset of target-context word pairs from a given text corpus.
- The word embeddings are learned using stochastic gradient descent (SGD).

## Sources
- deep learning for NLP
- google paper for word2vec

