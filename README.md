# Introduction to AI Workshop — Fall 2026

This repository contains the notebooks and datasets used for UIC's **Introduction to AI Workshop**.

## Workshop overview

- **Date:** Sunday, November 22, 2026
- **Time:** 9:00 a.m.–4:00 p.m. CST
- **Location:** Computer Design, Research, and Learning Center, room CDRLC 1422, at UIC
- **Audience:** UIC undergraduate students with Python programming experience
- **Format:** In-person, with full participation required
- **Provided:** Lunch and a certificate of participation
- **Funding:** UIC College of Engineering
- **Contact:** Prof. Gonzalo Bello ([gabellol@uic.edu](mailto:gabellol@uic.edu))

The workshop introduces fundamental concepts in artificial intelligence and machine learning through hands-on programming activities. Topics include deep learning, large language models, neural networks, image classification, and text generation with PyTorch, as well as the risks and ethical issues associated with AI.

The workshop is open to all UIC undergraduate students. Preference is given to students who have taken or are taking CS 107, CS 109, CS 111, or an equivalent course. Students from groups historically underrepresented in computer science are particularly encouraged to apply. Applications are reviewed on a rolling basis until all seats are filled, and submitting an application does not guarantee participation.

Read about a [previous UIC workshop](https://cs.uic.edu/news-stories/workshop-allows-students-to-explore-data-science/).

## Workshop materials

### Part 1: Neural networks and image classification

The first part of the workshop introduces neural networks with TensorFlow and progresses from a basic model to convolutional image classification.

1. [Simple neural network](Part%201/01-simple-neural-network.ipynb) — Builds a single-neuron model that learns a numerical relationship.
2. [Handwritten digit classification](Part%201/02-handwritten-digit-classification.ipynb) — Trains a dense neural network to classify handwritten digits from the MNIST dataset.
3. [Convolutional neural network](Part%201/03-convolutional-neural-network.ipynb) — Improves MNIST digit recognition with convolution and pooling layers.
4. [Fashion-MNIST mini-project](Part%201/04-fashion-mnist-mini-project.ipynb) — Applies dense and convolutional models to clothing image classification.

### Part 2: Transformers and text generation

The second part introduces natural language processing and the transformer architecture used by modern large language models. It progresses from training a transformer from scratch to generating text with a pre-trained GPT-2 model and fine-tuning it on a custom corpus.

1. [Transformer text generation](Part%202/01-transformer-text-generation.ipynb) — Tokenizes text, builds a vocabulary, and trains a TensorFlow transformer to predict words and generate new text.
2. [GPT-2 fine-tuning](Part%202/02-gpt2-fine-tuning.ipynb) — Generates text with a pre-trained GPT-2 model, fine-tunes it on a custom corpus, and compares the results.
3. [GPT-2 text-generation mini-project](Part%202/03-gpt2-text-generation-mini-project.ipynb) — Fine-tunes GPT-2 on *The Great Gatsby* and records observations about the generated text before and after fine-tuning.

#### Text datasets

The Part 2 notebooks accept an uploaded plain-text corpus for training or fine-tuning.

- [The Red-Headed League](Part%202/Data/TheRedHeadedLeague.txt) — A Sherlock Holmes story provided as model-ready plain text.
- *The Great Gatsby* by F. Scott Fitzgerald — Provided as [model-ready plain text](Part%202/Data/the-great-gatsby.txt) and a [193-page PDF source](Part%202/Data/the-great-gatsby.pdf).
