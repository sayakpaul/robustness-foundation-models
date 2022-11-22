# Foundational Robustness of Foundation Models (NeurIPS 2022 tutorial)

This repository holds code and other relevant files for the NeurIPS 2022 tutorial: [**Foundational Robustness of Foundation Models**](https://sites.google.com/view/neurips2022-frfm-turotial/) by [Pin-Yu Chen (IBM Research)](https://sites.google.com/site/pinyuchenpage/home), [Sijia Liu (Michigan State University)](https://lsjxjtu.github.io/), and [Sayak Paul (Hugging Face)](https://sayak.dev).

<div align="center">
<img src=https://user-images.githubusercontent.com/22957388/194623106-147c26fc-7350-4c28-9f01-a49e893e7ee2.png width=600/>
</div>

For details on schedule and the tutorial outline, please refer to our [tutorial website](https://sites.google.com/view/neurips2022-frfm-turotial/). You can also find the tutorial listing on [IBM Research](https://research.ibm.com/publications/foundational-robustness-of-foundation-models).

## Navigating the codebase

We provide code for analytical tools for two types of models: vision and code. Below provides a high-level
overview of what `code` and `vision_models` directories contain:

```bash
vision_models
├── probing_transformer_models
│   ├── attention_distance
│   ├── attention_maps
│   ├── linear_projections
│   └── positional_embeddings
├── representation_effectiveness
│   ├── fourier_heatmap
│   ├── masking
│   ├── pgd_attacks
│   └── spectral_decomposition
└── robustness_eval
```

```bash
code
├── Attack.ipynb
```

Each directory provides a standalone `README.md` with instructions about executing the
scripts / notebooks.

## Slides

You can find the slides in the `slides` directory.

## Acknowledgements

We thank [Jinghan Jia (Michigan State University)](https://www.linkedin.com/in/jinghan-jia-5194451ba) for contributing the code for evaluating "code" models.
