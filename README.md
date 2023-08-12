# DataDAM: Efficient Dataset Distillation with Attention Matching
Official implementation of "DataDAM: Efficient Dataset Distillation with Attention Matching", published as a conference paper at ICCV 2023.
## Abstract
Researchers have long tried to minimize training costs in deep learning while maintaining strong generalization across diverse datasets. Emerging research on dataset distillation aims to reduce training costs by creating a small synthetic set that contains the information of a larger real dataset and ultimately achieves test accuracy equivalent to a model trained on the whole dataset. Unfortunately, the synthetic data generated by previous methods are not guaranteed to distribute and discriminate as well as the original training data, and they incur significant computational costs. Despite promising results, there still exists a significant performance gap between models trained on condensed synthetic sets and those trained on the whole dataset. In this paper, we address these challenges using efficient Dataset Distillation with Attention Matching (DataDAM), achieving state-of-the-art performance while reducing training costs. Specifically, we learn synthetic images by matching the spatial attention maps of real and synthetic data generated by different layers within a family of randomly initialized neural networks. Our method outperforms the prior methods on several datasets, including MNIST, CIFAR10/100, TinyImageNet, and ImageNet-1K, across most of the settings, and achieves improvements of up to 6.5\% and 4.1\% on CIFAR100 and ImageNet-1K, respectively. We also show that our high-quality distilled images have practical benefits for downstream applications, such as continual learning and neural architecture search.
<p align="center">
<img src="https://github.com/AhmadSajedipro/DataDAM/blob/main/figs/DataDAM%20pipeline.png" width="600" height="400">
</p>
