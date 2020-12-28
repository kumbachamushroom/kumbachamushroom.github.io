---
title: "Using the SincTDNN architecture with pyannote-audio for speaker verification"
read_time: true
comments: false
share: true
related: false
categories:
  - Speaker verification
  - Neural Networks
  - Tutorials
---

In this tutorial/post I will be discussing how to use the pre-trained SincTDNN model found in the pyannote-audio toolkit for speaker verification, the docs are pretty vague about a lot of things so I hope this is informative to somebody, somewhere!

Before we start, for this to make sense you need a moderate understanding of [speaker verification](), [neural network embeddings](https://towardsdatascience.com/neural-network-embeddings-explained-4d028e6f0526) and [cosine similarity](https://www.machinelearningplus.com/nlp/cosine-similarity/#:~:text=Cosine%20similarity%20is%20a%20metric,in%20a%20multi%2Ddimensional%20space.&text=The%20smaller%20the%20angle%2C%20higher%20the%20cosine%20similarity.).

# SincTDNN?
Yeah, that's a mouthfull. Before we begin, SincTDNN refers
