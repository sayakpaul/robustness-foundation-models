# Foundational Robustness of Foundation Models (NeurIPS 2022 tutorial)

This repository holds code and other relevant files for the NeurIPS 2022 tutorial: [**Foundational Robustness of Foundation Models**](https://sites.google.com/view/neurips2022-frfm-turotial/) by [Pin-Yu Chen (IBM Research)](https://sites.google.com/site/pinyuchenpage/home), [Sijia Liu (Michigan State University)](https://lsjxjtu.github.io/), and [Sayak Paul (Carted)](https://sayak.dev).

<div align="center">
<img src=https://user-images.githubusercontent.com/22957388/187126670-44528423-c4f2-4857-bc09-41380b2adeb8.png width=600/>
</div>

## Schedule

TBA

## Outline

TBA

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
(TBA)
```

Each directory provides a standalone `README.md` with instructions about executing the
scripts / notebooks.
