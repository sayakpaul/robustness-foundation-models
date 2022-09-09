This directory will contain code (notebooks / scripts) for probing the representations
learned by vision models that are based on Transformers [1].

## Code navigation

Each directory provides notebook(s) for probing the representations from a vision transformer type model. We focus on the vanilla
ViT [2], DINO [5], and DeiT [6]. 

* `attention-maps` shows how to generate attention maps from individual attention heads from the final transformer block. (Visually,) best results were obtained with DINO. Techniques include attention flow and attention rollout.
* `attention-distance` deals with computing mean attention distance of the different attention heads.
* `linear-projections` shows visualizations of the linear projection filters learned by ViTs.
* `positional-embeddings` shows visualizations of the similarities of the positional embeddings learned by ViTs.

These notebooks are based on the techniques investigated in [2, 3, 4, 5]. The notebooks have been taken from [this repository](https://github.com/sayakpaul/probing-vits/).  

## References

[1] Vaswani, Ashish, et al. Attention Is All You Need. NeurIPS 2017, https://doi.org/10.48550/arXiv.1706.03762.

[2] Dosovitskiy, Alexey, et al. An Image Is Worth 16x16 Words: Transformers for Image Recognition at Scale. ICLR 2021, https://doi.org/10.48550/arXiv.2010.11929.

[3] Raghu, Maithra, et al. Do Vision Transformers See Like Convolutional Neural Networks? NeurIPS 2021, https://doi.org/10.48550/arXiv.2108.08810.

[4] Abnar, Samira, and Willem Zuidema. Quantifying Attention Flow in Transformers. ACL 2020, https://doi.org/10.48550/arXiv.2005.00928.

[5] Caron, Mathilde, et al. Emerging Properties in Self-Supervised Vision Transformers. ICCV 2021, https://doi.org/10.48550/arXiv.2104.14294.

[6] Touvron, Hugo, et al. Training Data-Efficient Image Transformers & Distillation through Attention. ICML 2021, https://doi.org/10.48550/arXiv.2012.12877.
