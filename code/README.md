This directory contains a self-contained notebook named `Attack.ipynb` (runnable on Google Colab) for evaluating the robustness of programming language models that are based on Transformers [1].

## Code navigation

This directory provide the notebook for evaluating robustness of programming language models by using two  attack generation methods [2, 3] in code domain. We focus on the code summarization task, and provide three models to compare their performance. 

* Supervised training.
* Contrastive learning (Contracode) [4].
* Robustness-aware Contrastive learning (CLAW) [5].

 

## References

[1] Vaswani, Ashish, et al. Attention Is All You Need. NeurIPS 2017, https://doi.org/10.48550/arXiv.1706.03762.

[2] Henke, Jordan, et al. "Semantic Robustness of Models of Source Code." 2022 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER). IEEE, 2022, https://ieeexplore.ieee.org/abstract/document/9825895.

[3] Srikant, Shashank, et al. "Generating Adversarial Computer Programs using Optimized Obfuscations." International Conference on Learning Representations. 2020, https://openreview.net/pdf?id=PH5PH9ZO_4.

[4] Jain, Paras, and Ajay Jain. "Contrastive Code Representation Learning." Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing. 2021. , https://arxiv.org/pdf/2007.04973.pdf.

[5] Jinghan Jia, Srikant, Shashank, et al. "Having Both: Robust and Accurate Code Models ." 
