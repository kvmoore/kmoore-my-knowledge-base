---
title: Recurrent Neural Networks
date: 2025-10-02
---

The way Recurrent Neural Networks work is through a looping that processes sequences allowing information to persist over time. The output of the network is fed back into itself creating a chain-like loop. This network also uses Backpropagation so that weight updates can occur.  They are different from FNNs and CNNs in that they are designed to process sequential and time-dependent data. RNNs take the current input and the hidden state (working memory) from previous states creating a form of memory. Because of this the network can capture relationships between elements and can understand a sentence or speech patterns, since they can remember these previous steps in a sequence, this works well for things like natural language processing, speech to text and music generation.\
 
More advanced variants were developed to address a vanishing gradient problem (improvements). These are called Long Short-Term Memory networks (LSTMs) and Gated Recurrent Units (GRUs). These control the flow of information better and allow the network to relevant information longer and forget irrelevant data significantly improving performance.


## Navigation
[[index|Back to Types Index]]  
[[03 CNNs Convolutional Neural Networks|Previous: Convolutional Neural Networks]]  
[[05 Transformers|Next: Transformers]]

---
