# Language-Modelling-Zero-to-One

This repository offers an in-depth journey into the world of language modeling, guiding you from foundational models like bigrams to sophisticated architectures such as Transformers. By tracing the evolution of these models, you'll gain hands-on experience with various techniques and their practical implementations.

The models in this repository are trained on the Tiny Shakespeare dataset, providing a focused and manageable context for experimentation.

Inspired by Andrew Karpathy's NanoGPT series, this project aims to make complex concepts in language modeling accessible and engaging. 😊

---- 

## Bigram Model
Bigram models predict the next word in a sequence based on the previous word, capturing the basic relationship between word pairs.

**`Bigram models learn that some words are more likely to occur after others`**

<img height="700" width="100%" alt="bigram-learnings" src="https://github.com/user-attachments/assets/b1fdb0fc-13a1-446b-9111-ba7dd15b698e">


### Text Generation using Bigram Model:
<img width="908" alt="bigram-generation" src="https://github.com/user-attachments/assets/e9adca69-5816-4d88-9b5c-35bba0245b71">

---

## Multi-Layer Perceptron (MLP)
MLP models consist of multiple layers of neurons, learning to map input data to the correct output by adjusting weights through backpropagation.

### Text Generation Before and After Learning:

| **Before Learning** | **After Learning** |
|---------------------|--------------------|
| <img height="150" alt="mlp_generation_without_training" src="https://github.com/user-attachments/assets/60452c1b-3351-4796-bd2a-7a5c49225620"> | <img width="500" alt="mlp_generation_after_training" src="https://github.com/user-attachments/assets/307cc8a3-3db3-4e70-825f-7e1458fd661e"> |

### Loss:
![mlp-loss](https://github.com/user-attachments/assets/f34eb9b9-9d18-4823-8d88-e34ab1559171)

---

## Character Level Recurrent Neural Networks (RNNs)
RNNs are designed to handle sequential data, allowing the model to maintain a memory of previous inputs to predict the next character in a sequence.

### Text Generation Before and After Learning:

| **Before Learning** | **After Learning** |
|---------------------|--------------------|
| <img height="150" alt="rnn_generation_without_training" src="https://github.com/user-attachments/assets/c1ba1b8a-2093-4b54-8c39-fc94d7b8dc04"> | <img width="400" alt="rnn_generation_after_training" src="https://github.com/user-attachments/assets/f635fbdf-d9a3-4593-8ff4-f90550b9109a"> |

### Loss:
![rnn_loss](https://github.com/user-attachments/assets/e082b7d3-122f-4ab5-ac56-1981402b7353)

## Transformer Model
Used the Decoder part of Transformers model for text-generation

| **Before Learning** | **After Learning** |
|---------------------|--------------------|
| <img height="150" alt="rnn_generation_without_training" src="https://github.com/user-attachments/assets/c1ba1b8a-2093-4b54-8c39-fc94d7b8dc04"> |  ![transformer-generated-text](https://github.com/user-attachments/assets/3d785aea-a509-4f99-b008-ffcc9017a74b) |

### Loss:
![transformer-loss](https://github.com/user-attachments/assets/8de494e1-ae31-4fd4-b340-a417f951bc04)

---
