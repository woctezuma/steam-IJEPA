# Steam I-JEPA: match banners with Meta AI's I-JEPA

This repository contains Python code to retrieve Steam games with similar store banners, using [Meta AI's **I**mage-based **J**oint-**E**mbedding **P**redictive **A**rchitecture (I-JEPA)][fb-ijepa-code].

Image similarity is assessed by the cosine similarity between image features encoded by I-JEPA.

![Similar vertical banners][wiki-cover]

## References

-   Meta AI's I-JEPA:
    - [Official blog post][fb-ijepa-blog]
    - [Official Github repository][fb-ijepa-code]
    - [Assran, Mahmoud, et al. *Self-Supervised Learning from Images with a Joint-Embedding Predictive Architecture*. CVPR 2023.][fb-ijepa-paper] 

<!-- Definitions -->

[wiki-cover]: <https://github.com/woctezuma/steam-IJEPA/wiki/img/illustration.jpg>

[fb-ijepa-blog]: <https://ai.meta.com/blog/yann-lecun-ai-model-i-jepa/>
[fb-ijepa-code]: <https://github.com/facebookresearch/ijepa>
[fb-ijepa-paper]: <https://arxiv.org/abs/2301.08243>

[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>
