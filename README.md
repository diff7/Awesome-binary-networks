# Awesome-binary-networks



#### INTRO 

Currently, there are two main directions to improving the performance of binary nets.**  
  
- The first direction is how to modify or to adjust the architecture to be suitable for binary weights. Mainly, we want to increase models capacity by adding more weights, but it should be done the right way. Since linear and convolutional layers take most of the computation most of the time, research mainly focus on binarizing only weights for these operations and relaxing other parts of the architecture to be real valued, parts such as batch norm, learnable scaling or activation values. This approach reduces computation costs but requires mixed precision computation. Therefore,  it is unclear if such networks can be efficiently executed without specific software and hardware solutions.  
  
- The second direction is focused on optimization. Since weights are binarized, we need to come up with some solution on how to backpropagate through binarization function.  
  
Unsurprisingly, approaches based on architecture modification show marginally better results.  
  
Papers are split into two parts. Introduction papers, which I recommend reading first to get familiar with the problem and all others.


#### READ FIRST


2016 <br>
Binarized Neural Networks: Training Deep Neural Networks with Weights and Activations Constrained to +1 or -1 
https://arxiv.org/abs/1602.02830 


2016 <br>
XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks
[Mohammad Rastegari](https://arxiv.org/search/cs?searchtype=author&query=Rastegari%2C+M), [Vicente Ordonez](https://arxiv.org/search/cs?searchtype=author&query=Ordonez%2C+V), [Joseph Redmon](https://arxiv.org/search/cs?searchtype=author&query=Redmon%2C+J), [Ali Farhadi](https://arxiv.org/search/cs?searchtype=author&query=Farhadi%2C+A)
https://arxiv.org/abs/1603.05279


2017 <br>
The High-Dimensional Geometry of Binary Neural Networks
[Alexander G. Anderson](https://arxiv.org/search/cs?searchtype=author&query=Anderson%2C+A+G), [Cory P. Berg](https://arxiv.org/search/cs?searchtype=author&query=Berg%2C+C+P)
https://arxiv.org/pdf/1705.07199.pdf

2020 <br>
Binary neural networks: A survey
https://www.sciencedirect.com/science/article/pii/S0031320320300856

<hr>

#### READ AFTER

2017 <br>
Towards Accurate Binary Convolutional Neural Network #toread
[Xiaofan Lin](https://arxiv.org/search/cs?searchtype=author&query=Lin%2C+X), [Cong Zhao](https://arxiv.org/search/cs?searchtype=author&query=Zhao%2C+C), [Wei Pan](https://arxiv.org/search/cs?searchtype=author&query=Pan%2C+W)
https://arxiv.org/abs/1711.11294


2018 <br>
Bi-Real Net: Enhancing the Performance of 1-bit CNNs With Improved Representational Capability and Advanced Training Algorithm
https://arxiv.org/abs/1808.00278

2018 <br>
Binary Ensemble Neural Network: More Bits per Network or More Networks per Bit?
[Shilin Zhu](https://arxiv.org/search/cs?searchtype=author&query=Zhu%2C+S), [Xin Dong](https://arxiv.org/search/cs?searchtype=author&query=Dong%2C+X), [Hao Su](https://arxiv.org/search/cs?searchtype=author&query=Su%2C+H)
https://arxiv.org/pdf/1806.07550.pdf

2019 <br>
Structured Binary Neural Networks for Image Recognition
[Bohan Zhuang](https://arxiv.org/search/cs?searchtype=author&query=Zhuang%2C+B), [Chunhua Shen](https://arxiv.org/search/cs?searchtype=author&query=Shen%2C+C), [Mingkui Tan](https://arxiv.org/search/cs?searchtype=author&query=Tan%2C+M), [Peng Chen](https://arxiv.org/search/cs?searchtype=author&query=Chen%2C+P), [Lingqiao Liu](https://arxiv.org/search/cs?searchtype=author&query=Liu%2C+L), [Ian Reid](https://arxiv.org/search/cs?searchtype=author&query=Reid%2C+I)
https://arxiv.org/abs/1909.09934

2019 <br>
Circulant Binary Convolutional Networks: Enhancing the Performance of 1-bit   DCNNs with Circulant Back Propagation  
jironronggChunlei Liu, Wenrui Ding, Xin Xia, Baochang Zhang, j Jiaxin Gu, jiergrong   Jianzhuang Liu, Rongrong Ji, David Doermann
https://arxiv.org/pdf/1910.10853.pdf

2020 <br>
Widening and Squeezing: Towards Accurate and Efficient QNNs
[Chuanjian Liu](https://arxiv.org/search/cs?searchtype=author&query=Liu%2C+C), [Kai Han](https://arxiv.org/search/cs?searchtype=author&query=Han%2C+K), [Yunhe Wang](https://arxiv.org/search/cs?searchtype=author&query=Wang%2C+Y), [Hanting Chen](https://arxiv.org/search/cs?searchtype=author&query=Chen%2C+H), [Qi Tian](https://arxiv.org/search/cs?searchtype=author&query=Tian%2C+Q), [Chunjing Xu](https://arxiv.org/search/cs?searchtype=author&query=Xu%2C+C)
https://arxiv.org/abs/2002.00555
 
2020 <br>
ReActNet: Towards Precise Binary Neural Network with Generalized Activation Functions
https://arxiv.org/abs/2003.03488
https://github.com/liuzechun/ReActNet


2020 <br>
ReActNet: Towards Precise Binary Neural Network with Generalized Activation Functions
https://link.springer.com/chapter/10.1007/978-3-030-58568-6_9


2020 <br>
Training Binary Neural Networks using the Bayesian Learning Rule
https://arxiv.org/abs/2002.10778


2021 <br>
Multi-Prize Lottery Ticket Hypothesis: Finding Accurate Binary Neural Networks by Pruning A Randomly Weighted Network
https://arxiv.org/abs/2103.09377

2021 <br>
FracBNN: Accurate and FPGA-Efficient Binary Neural Networks with Fractional Activations #toread
https://dl.acm.org/doi/abs/10.1145/3431920.3439296

2021 <br>
Fast Walsh-Hadamard Transform and Smooth-Thresholding Based Binary  Layers in Deep Neural Networks
https://openaccess.thecvf.com/content/CVPR2021W/BiVision/papers/Pan_Fast_Walsh-Hadamard_Transform_and_Smooth-Thresholding_Based_Binary_Layers_in_Deep_CVPRW_2021_paper.pdf


2021 <br>
Finding Everything within Random Binary Networks
https://arxiv.org/abs/2110.08996

2022 <br>
Self-distribution binary neural networks
https://link.springer.com/article/10.1007/s10489-022-03348-z

2022 <br>
An Empirical study of Binary Neural Networks' Optimisation
https://openreview.net/forum?id=rJfUCoR5KX

2022 <br>
Block Walsh-Hadamard Transform Based Binary Layers in Deep Neural Networks
https://arxiv.org/abs/2201.02711







