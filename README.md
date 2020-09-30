# ResNet Pytorch implementation for MNIST classification
This repo replicates the ResNet on MNIST/FashionMNIST dataset, using PyTorch torchvision model. The torchvision model is reused by splitting the ResNet into a feature extractor and a classifier. And the training is conducted with/without the pre-trained model.

The details of the implementation can be found in the [notebook](https://github.com/JiahongChen/resnet-pytorch/blob/master/ResNet_MNIST_Pytorch.ipynb). This repo also provides an test on FashionMNIST dataset.

# Citation
 
If you find this repo useful, please cite the original paper

```
@inproceedings{he2016deep,
  title={Deep residual learning for image recognition},
  author={He, Kaiming and Zhang, Xiangyu and Ren, Shaoqing and Sun, Jian},
  booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition},
  pages={770--778},
  year={2016}
}
```
