#Towards thinner convolutional neural networks through gradually global pruning

Convolutional neural networks (CNNs) have achieved tremendous progress in many pattern recognition tasks. However, CNNs are always trapped by their huge amount of parameters when facing with resource-limited devices. This situation drives the development of a new research topic called Deep Compression, which aims to reduce the size of deep learning models. Model pruning is a main method to reduce the
complexity of deep learning model. According to the difference of pruning targets, model pruning could be divided into several granularities, from dropping an entire layer to just cutting off a single connection. In this paper, we propose a gradually global pruning scheme for neuron level pruning. By gradually selecting and pruning the redundant neurons in whole network, we could make the most of neurons and find out a near-optimal structure for the model. As a result, thinner networks with less neurons in each layer are obtained. Our scheme could automatically find a thinner network structure with given performance.

#reference:

Zhengtao Wang, Ce Zhu, Zhiqiang Xia, Qi Guo, Yipeng Liu, “Towards thinner convolutional neural networks through gradually global pruning, ” The 2017 IEEE International Conference on Image Processing (ICIP 2017), Beijing, China, September 17-20, 2017.
