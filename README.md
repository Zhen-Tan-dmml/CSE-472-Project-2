# CSE-472-Project-2: Understanding Text Classifiers with Counterfactual Explanation

### Mitigate Impact Spurious Correlation for Text Classification with Counterfactual Methods
|Name|Paper|Code
|---|---|---|
|CLP|[[AAAI 2019] Counterfactual Fairness in Text Classification through Robustness](https://arxiv.org/pdf/1809.10610.pdf)|[PyTorch](https://github.com/SaiSakethAluru/Counterfactual-fairness)
|Corsair|[[ACL 2021] Counterfactual Inference for Text Classification Debiasing](https://aclanthology.org/2021.acl-long.422.pdf)|[PyTorch](https://github.com/qianc62/Corsair)
|AGC|[[AAAI 2021] Robustness to Spurious Correlations in Text Classification via Automatically Generated Counterfactuals](https://dl.acm.org/doi/pdf/10.1145/3306618.3317950)|[Pytorch](https://github.com/tapilab/aaai-2021-counterfactuals)


### Explaining Machine Learning Classifiers through Diverse Counterfactual Explanations
|Name|Paper|Code
|---|---|---|
|DiCE|[[FAT 2021] Explaining Machine Learning Classifiers through Diverse Counterfactual Explanations](https://arxiv.org/abs/1905.07697)|[Tensorflow/PyTorch/sklearn](https://github.com/interpretml/DiCE)

1. Model-agnostic methods
- Randomized sampling
- KD-Tree (for counterfactuals within the training data)
- Genetic algorithm

2. Gradient-based methods
- An explicit loss-based method described in Mothilal et al. (2020) (Tensorflow/PyTorch)
- A Variational AutoEncoder (VAE)-based method described in Mahajan et al. (2019)
