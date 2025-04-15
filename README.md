# Knowledge-Distillation-Stanford40-and-CIFAR100

This project uses the concept of [Knowledge Distillation via Attention-based Feature Matching](https://arxiv.org/abs/2102.02973) and its [pytorch implementation](https://github.com/clovaai/attention-feature-distillation) in order to transfer knowledge from a source neural network(**Teacher Network**) to a target neural network(**Student Network**) on two datasets.\ 
# WRN_ST40.ipynb
**Teacher network:** resnet34im = ”ResNet-34 model from Deep Residual Learning for Image Recognition [Article](https://arxiv.org/pdf/1512.03385)\
**Student network:** resnet18im = ”ResNet-18 model from Deep Residual Learning for Image Recognition [Article](https://arxiv.org/pdf/1512.03385)\
**Dataset**: Stanford40
# CIFAR100.ipynb
**Teacher network:** WRN40X2 = WideResNet(depth=40, Widen factor=2)\
**Student network:** WRN16X2 = WideResNet(depth=16, Widen factor=2)\
**Dataset**: Stanford40 **Or** CIFAR100

# Requirement
In onder to make the Stanfor40 dataset to be suitable for this training process, it should be prepared with one of my repository [Stanford40DataLoader](https://github.com/m-zafari/Stanford40DataLoader)

Furthermore, some minor change which are necessary for running the training process and the program in Jupiter Notebook is also made in the files below:
[Required files and datasets](https://drive.google.com/drive/folders/1U8pX87HGUYdhyCAtsvWpe4Ac_oHS3vwc?usp=sharing)



