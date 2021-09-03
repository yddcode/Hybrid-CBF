# Hybrid-CBF: A hybrid classification and binarization framework for historical Tai Le document image
一个混合分类和二值化的框架用于德宏傣文古籍文档

本文提出一种混合分类和二值化的架构用于历史德宏傣文文档图像，即Hybrid-CBF。首先，德宏傣文古籍因背景污染程度不同导致无法用一种二值化方法解决，提出历史德宏傣文文档图像按噪声水平估计值进行聚类，将污染的背景噪声分类为不同等级。其次，针对不同污染等级的历史文档使用相应最优的二值化方法。为此，在Hybrid-CBF中，包含提出的两种基于深度神经网络架构的德宏傣文古籍二值化结构，即TL-Merge UNet和TL-TC UNet。在构建的德宏傣文古籍图像二值化数据集(Tai Le historical document image binarization dataset, TLHDIBD2021 https://github.com/yddcode/TLHDIBD2021)、PHIBD和H-DIBCO 2014 2016数据集上与许多经典和最新的方法相比，所提出的框架在准确性和泛化性能方面具有较大的提升。
