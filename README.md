# Deep-lab
This repository was inspired by : [Dan Suh's - Deep Learning Roadmap](https://github.com/dansuh17/deep-learning-roadmap).

> This repository is my digital laboratory. It will allow me to deepen my knowledge, to work with different architectures and maybe to gather new ideas outside my research field.


## Environment

### Environment creation 
```bash
conda create -n deep-lab-p3.9 python=3.9
conda activate deep-lab-p3.9
conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1
pip install tensorflow-gpu==2.10
pip install -r requirements.txt
```

### Environment launching
```bash
jupyter lab .
```


---
## Knowledge base
### Courses & lectures I followed
- My master's lectures
- [Stanford's CS231n Class Notes](http://cs231n.github.io/)
  
### Classic CNN Architectures
- [x] **LeNet5** (1998) [[paper](http://vision.stanford.edu/cs598_spring07/papers/Lecun98.pdf)] - Impl. date : 05/2022
    - LeCun et al. "Gradient-Based Learning Applied to Document Recognition"
- [x] **AlexNet** (2012) [[paper](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks)] - Impl date : 01/2023
    - Alex Krizhevsky et al. "ImageNet Classification with Deep Convolutional Neural Networks"
- [ ] **ZFNet** (2013) [[paper](https://arxiv.org/abs/1311.2901)]
    - Zeiler et al. "Visualizing and Understanding Convolutional Networks"
- [x] **VGG** (2014) - Impl. date : 01/2023
    - Simonyan et al. "Very Deep Convolutional Networks for Large-Scale Image Recognition" (2014) [Google DeepMind & Oxford's] [[paper](https://arxiv.org/abs/1409.1556)]
- [ ] **GoogLeNet**, a.k.a **Inception v.1** (2014) [[paper](https://arxiv.org/abs/1409.4842)]
    - Szegedy et al. "Going Deeper with Convolutions" [Google]
    - Original [LeNet page](http://yann.lecun.com/exdb/lenet/) from Yann LeCun's homepage.
    - [ ] **Inception v.2 and v.3** (2015) Szegedy et al. "Rethinking the Inception Architecture for Computer Vision" [[paper](https://arxiv.org/abs/1512.00567)]
    - [ ] **Inception v.4 and InceptionResNet** (2016) Szegedy et al. "Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning" [[paper](https://arxiv.org/abs/1602.07261)]
    - "A Simple Guide to the Versions of the Inception Network" [[blogpost](https://towardsdatascience.com/a-simple-guide-to-the-versions-of-the-inception-network-7fc52b863202)]
- [ ] **ResNet** (2015) [[paper](https://arxiv.org/abs/1512.03385)] - Impl. date : in progress
    - He et al. "Deep Residual Learning for Image Recognition"
- [ ] **Xception** (2016) [[paper](https://arxiv.org/abs/1610.02357)]
    - Chollet, Francois - "Xception: Deep Learning with Depthwise Separable Convolutions"
- [ ] **MobileNet** (2016) [[paper](https://arxiv.org/abs/1704.04861)]
    - Howard et al. "MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications"
    - A nice paper about reducing CNN parameter sizes while maintaining performance.
- [ ] **DenseNet** (2016) [[paper](https://arxiv.org/abs/1608.06993)]
    - Huang et al. "Densely Connected Convolutional Networks"

### Digital Signal processing & chemometrics implementation
- [x] **CNNVS** (2016) [[paper - Elsevier : code will not be accessible on this repository)](https://doi.org/10.1016/j.aca.2016.12.010)] - Impl. date : 12/2022
    - Acquarelli et al. "Convolutional neural networks for vibrational spectroscopic data analysis"
- [x] **DeepSpectra** (2018) [[paper - Elsevier : code will not be accessible on this repository)](https://doi.org/10.1016/j.aca.2019.01.002)] : Impl. date : 12/2022
    - Zhang et al. "DeepSpectra: An end-to-end deep learning approach for quantitative spectral analysis"
