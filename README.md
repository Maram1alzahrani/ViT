# Vision Transformer (ViT)

### Understanding ViT and the motivation behind ViTAEv2

A 12-section teaching notebook by Maram Alzahrani. Sections 1–11 follow an image through patch extraction, embeddings, attention, and classification. Section 12 explains the selected ViTAEv2 paper: its motivation, RC/NC architecture, four-stage design, and an accuracy–memory trade-off from Table 8.

[Open the notebook](Vision_Transformer_Tutorial.ipynb) · [Run in Colab](https://colab.research.google.com/github/Maram1alzahrani/ViT/blob/main/Vision_Transformer_Tutorial.ipynb)

## Contents

The foundations cover patch extraction, linear embeddings, CLS and position tokens, Q/K/V, multi-head attention, encoder blocks, classification, and learning. Four short PyTorch examples show tensor shapes and a complete forward pass.

The paper discussion defines inductive bias, explains how PRM and PCM fit into Reduction and Normal Cells, and uses the paper's Figure 3 to distinguish ViTAEv2's stage-wise architecture from the introductory ViT example. A two-row comparison from Table 8 explains why the authors chose window attention in the first two stages and full attention in the last two.

## Present

Use Sections 1–11 as background, then focus on Section 12: **problem → proposed cells → ViTAEv2 architecture → experimental evidence**. The architecture figure is embedded in the notebook.

## Run

Use Python 3.10+ with PyTorch installed (`python -m pip install -r requirements.txt`). Open the notebook in Jupyter, VS Code, or Colab and run the cells in order. The examples use a synthetic image and do not require a dataset download.

The tiny model has random weights and demonstrates the forward pass only. It does not implement PRM, PCM, or the ViTAEv2 backbone, and it does not reproduce the paper's training or accuracy results. The experiment discussed in Section 12 is explicitly attributed to the paper.

## References

- [ViTAEv2: Vision Transformer Advanced by Exploring Inductive Bias for Image Recognition and Beyond](https://doi.org/10.1007/s11263-022-01739-w) · [arXiv v2 PDF](https://arxiv.org/pdf/2202.10108v2)
- [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale](https://arxiv.org/abs/2010.11929)
