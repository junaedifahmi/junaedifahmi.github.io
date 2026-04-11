---
title: Towards Novel Target Discovery Through Open-Set Domain Adaptation
publish: true
tags:
  - review
  - osda
  - ai
---
# Towards Novel Target Discovery Through Open-Set Domain Adaptation

## Paper Abstract

Open-set domain adaptation (OSDA) considers that the target domain contains samples from novel categories unobserved in external source domain. Unfortunately, existing OSDA methods always ignore the demand for the information of unseen categories and simply recognize them as “unknown” set without further explanation. This motivates us to understand the unknown categories more specifically by exploring the underlying structures and recovering their interpretable semantic attributes. In this paper, we propose a novel framework to accurately identify the seen categories in target domain, and effectively recover the semantic attributes for unseen categories. Specifically, structure preserving partial alignment is developed to recognize the seen categories through domain-invariant feature learning. Attribute propagation over visual graph is designed to smoothly transit attributes from seen to unseen categories via visual-semantic mapping. Moreover, two new cross-domain benchmarks are constructed to evaluate the proposed framework in the novel and practical challenge. Experimental results on open-set recognition and semantic recovery demonstrate the superiority of the proposed method over other compared baselines.

## Bib Citation
```bibtex
@misc{jing2021noveltargetdiscoveryopenset,
      title={Towards Novel Target Discovery Through Open-Set Domain Adaptation}, 
      author={Taotao Jing and Hongfu Liu and Zhengming Ding},
      year={2021},
      eprint={2105.02432},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2105.02432}, 
}
```

# Research Question
* how to accurately identify seen and unseen categories in target domain with well-labeled source knowledge;
* how to effectively recover the missing attributes of unseen categories.

# Methodology

# Findings

# Critiques

## Strength

## Limitation

## Personal Note
1. This paper is emphasize more into discovery of new class, which is esential for open-set domain adaptation. 
2. The paper is using joint dataset training, which assume on the training we have access to source domain dataset.

