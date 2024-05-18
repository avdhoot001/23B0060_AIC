Vision-Based Transformers (ViTs) are a class of deep learning models that apply the Transformer architecture, 
originally designed for natural language processing tasks,to image recognition problems. 
The core idea behind ViTs is to leverage the self-attention mechanism of Transformers to capture long-range dependencies and global context in images
which traditional Convolutional Neural Networks (CNNs) handle differently.

ViT special characteristics:
Patch Embedding:ViTs divide an image into fixed-size patches (e.g., 16x16 pixels) and linearly embed each patch into a vector. 
                This process transforms the 2D image into a sequence of 1D patch embeddings, akin to the sequence of word embeddings in NLP tasks.
Positional Encoding:Since Transformers lack an inherent notion of order, positional encodings are added to the patch embeddings to retain the spatial information
                          of the patches within the image.
Self-Attention Mechanism:The self-attention mechanism allows ViTs to model relationships between patches,
                         capturing global context more effectively than the local receptive fields of CNNs.
Transformers Architecture:The architecture comprises multiple layers of multi-head self-attention and feed-forward neural networks,
                          with layer normalization and residual connections.

ADVANTAGES OF ViT:
Global Context
Simpler Architecture

DISADVANTAGES OF ViT:
efficiency(quadratic)
huge data and computational resources required
interpretability

DIFFERENCES:
1)CNNs have strong inductive bias while ViT have minimal inductive bias
2)CNNs are efficient on small datasets while ViT require large datasets.
3)CNN excels in local feature extraction and hierarchical patterns while ViT excel in large-scale classification tasks and global context.
