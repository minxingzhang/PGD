## Implementation of Projected Gradient Descent (PGD)

We provide our [PyTorch](https://pytorch.org/) implementations of PGD-based adversarial training [1], which currently supports the datasets of [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html), [CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html) and [SVHN](http://ufldl.stanford.edu/housenumbers/), and the model architectures of [ResNet](https://arxiv.org/abs/1512.03385), [VGG-11](https://arxiv.org/abs/1409.1556), [DenseNet](https://arxiv.org/abs/1608.06993), [PreActResNet](https://arxiv.org/abs/1603.05027) and [WideResNet](https://arxiv.org/abs/1605.07146), under $\ell_\infty$ and $\ell_2$ perturbations.

### News

- [2024.08.09] We released our version of PGD-based adversarial training implementations based on [Robust Overfitting](https://github.com/locuslab/robust_overfitting).

### Usage

__Get the codes__

```
git clone https://github.com/minxingzhang/PGD.git
cd PGD
```

__Adversarially train a MODEL on a DATASET__

```
python -u PGD_train.py \
       --dataset <Which Dataset> \
       --model <Which Model> \
       --norm <Which Perturbation Norm>
```

### Reference

[1] PGD: [https://arxiv.org/abs/1706.06083](https://arxiv.org/abs/1706.06083)
