# Vision Transformer (ViT)

A 12-section notebook by Maram Alzahrani explaining how ViT turns an image into patches, processes them with a Transformer, and predicts a class. Four short PyTorch code examples show the tensor shapes and a complete forward pass.

[Open the notebook](Vision_Transformer_Tutorial.ipynb) · [Run in Colab](https://colab.research.google.com/github/Maram1alzahrani/ViT/blob/main/Vision_Transformer_Tutorial.ipynb)

## Contents

The notebook covers patch extraction, linear embeddings, position and CLS tokens, Q/K/V, multi-head attention, encoder blocks, classification, and learning. The last section briefly connects the core architecture to the selected ViTAEv2 paper.

## Run

Use Python 3.10+ with PyTorch installed (`python -m pip install -r requirements.txt`). Open the notebook in Jupyter, VS Code, or Colab and run the cells in order. The examples use a synthetic image and do not require a dataset download.

The tiny model has random weights and shows the forward pass only. It does not reproduce ViTAEv2 or report classification accuracy.

## References

- [ViTAEv2: Vision Transformer Advanced by Exploring Inductive Bias for Image Recognition and Beyond](https://doi.org/10.1007/s11263-022-01739-w)
- [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)
