# Official_Nonconvex_SGL
 Nonconvex Sparse Group Lasso for Deep Learning

This repository is adapted from the repository (https://github.com/AMLab-Amsterdam/L0_regularization).

Please cite the following if you use this code for your research:
```
@ARTICLE{Bui2021,
AUTHOR={Bui, Kevin and Park, Fredrick and Zhang, Shuai and Qi, Yingyong and Xin, Jack},   
TITLE={Structured Sparsity of Convolutional Neural Networks via Nonconvex Sparse Group Regularization},      
JOURNAL={Frontiers in Applied Mathematics and Statistics},      
VOLUME={6},      
PAGES={62},     
YEAR={2021},      
URL={https://www.frontiersin.org/article/10.3389/fams.2020.529564},       
DOI={10.3389/fams.2020.529564},      
ISSN={2297-4687}
}
```



- 将regularization作为模型和层的方法进行实现（只与模型参数有关）
- 优化似乎用的就是简单的随机梯度下降，并没有找到原文提到的优化算法。
