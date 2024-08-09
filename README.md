## Implementation of Projected Gradient Descent (PGD)

We provide our version of PGD implementations, which currently supports the datasets of [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html), [CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html) and [SVHN](http://ufldl.stanford.edu/housenumbers/), and the model architectures of [ResNet](https://arxiv.org/abs/1512.03385), [VGG-11](https://arxiv.org/abs/1409.1556), [DenseNet](https://arxiv.org/abs/1608.06993), [PreActResNet](Identity Mappings in Deep Residual Networks) and [WideResNet](https://arxiv.org/abs/1605.07146), under $\ell_\infty$ and $\ell_2$ perturbations.

### News

- [2024.08.09] We released our version of PGD implementations based on [Robust Overfitting](https://github.com/locuslab/robust_overfitting).

### Usage

`python -u PGD_train.py \
        --dataset <Which Dataset> --model <Which Model> --norm <Which Perturbation Norm>`
