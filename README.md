# Sparse-and-Imperceivable-attacks-Implementation

This repository is a PyTorch implementation of the Research paper "Sparse and Imperceivable Adversarial Attacks" by Francesco Croce and Matthias Hein of University of Tubingen

# Abstract

Numerous adversarial attacks have been shown to be capable of weakening neural networks. Highly sparse hostile attacks are particularly risky from a safety standpoint. On the other hand, sparse attacks generally result in massive pixelwise perturbations, making them potentially detectable. We provide a brand-new
black-box method for creating adversarial examples that aims to reduce the l0-distance from the source image. Extensive testing demonstrates that our attack is superior to or on par with the state of the art. We may also integrate further restrictions on the componentwise perturbation.
Our adversarial instances are virtually undetectable because we only allow pixel changes in regions of significant variance and refrain from allowing changes along axis-aligned edges. Additionally, we modify the Projected Gradient Descent attack to account for the componentwise integrating l0-norm limitations. In order to strengthen the resilience of classifiers against sparse and undetectable adversarial alterations, this enables us to do adversarial training.

<!-- Add the paper link -->

# Research Paper Link

[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Croce_Sparse_and_Imperceivable_Adversarial_Attacks_ICCV_2019_paper.pdf)

# Detailed explanation of the code

[Report](https://github.com/ayushabrol13/Sparse-and-Imperceivable-attacks-Implementation/blob/master/Report.pdf)
