# Vision Transformer (ViT) — Easy to Remember

A short, 12-part English tutorial by Maram Alzahrani. It follows one path:

**Image → Patches → Embeddings → Position + CLS → Attention → Prediction**

[Open the notebook](Vision_Transformer_Tutorial.ipynb) · [Run in Colab](https://colab.research.google.com/github/Maram1alzahrani/ViT/blob/main/Vision_Transformer_Tutorial.ipynb)

## Contents

Simple explanations of image patches, embeddings, position, CLS, Q/K/V, multi-head attention, Transformer blocks, and classification. Four small PyTorch code cells show the tensor shapes and a tiny ViT forward pass. Section 12 briefly connects ViT to the selected ViTAEv2 paper.

## Run

Use Python 3.10+ with PyTorch installed (`python -m pip install torch`). Open the notebook in Jupyter, VS Code, or Colab and run cells in order. No dataset download or training is required.

The code uses random weights to explain the forward pass. It does not reproduce or evaluate ViTAEv2.

## Papers

- [ViTAEv2: Vision Transformer Advanced by Exploring Inductive Bias for Image Recognition and Beyond](https://doi.org/10.1007/s11263-022-01739-w)
- [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)
