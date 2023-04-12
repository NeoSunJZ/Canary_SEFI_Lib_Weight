# Canary SEFI Lib Weight Release

Used to publish weights for PyTorch models, adversarial attacks, and defenses provided by Canary SEFI.

These weights are mainly derived from other open source project contributions and self-training. For the weights used from other open source projects, we will list their specific sources in detail and thank you most sincerely.

We welcome more people to contribute newer and more accurate weights for us. 

## Model Weight

We provide weights for the CIFAR-100, CIFAR-10 and FashionMNIST datasets. For the ImageNet dataset, the weights have been officially given by PyTorch/Torchvision, so they will not be repeated here.

### CIFAR-100

| Model        | Weight Name                            | Top-1 Acc.(%) | Source                                                       |
| ------------ | -------------------------------------- | ------------- | ------------------------------------------------------------ |
| MobileNet v2 | cifar100_mobilenetv2_x1_4-8a269f5e.pt  | 70.88         | Project: [PyTorch CIFAR Models](https://github.com/chenyaofo/pytorch-cifar-models) |
| MobileNet v2 | cifar100_mobilenetv2_x1_0-1311f9ff.pt  | 73.61         | Project: [PyTorch CIFAR Models](https://github.com/chenyaofo/pytorch-cifar-models) |
| MobileNet v2 | cifar100_mobilenetv2_x0_75-d7891e60.pt | 74.20         | Project: [PyTorch CIFAR Models](https://github.com/chenyaofo/pytorch-cifar-models) |
| MobileNet v2 | cifar100_mobilenetv2_x0_5-9f915757.pt  | 75.98         | Project: [PyTorch CIFAR Models](https://github.com/chenyaofo/pytorch-cifar-models) |
| ResNet       | cifar100_resnet20-23dac2f1.pt          | 68.83         | Project: [PyTorch CIFAR Models](https://github.com/chenyaofo/pytorch-cifar-models) |
| ResNet       | cifar100_resnet32-84213ce6.pt          | 70.16         | Project: [PyTorch CIFAR Models](https://github.com/chenyaofo/pytorch-cifar-models) |
| ResNet       | cifar100_resnet44-ffe32858.pt          | 71.63         | Project: [PyTorch CIFAR Models](https://github.com/chenyaofo/pytorch-cifar-models) |
| ResNet       | cifar100_resnet56-f2eff4c8.pt          | 72.63         | Project: [PyTorch CIFAR Models](https://github.com/chenyaofo/pytorch-cifar-models) |
