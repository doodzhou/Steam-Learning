@ARTICLE{ZHOU_TNNLS2022,
  author={Zhou, Peng and Wang, Ni and Zhao, Shu and Zhang, Yanping and Wu, Xindong},
  
  journal={IEEE Transactions on Neural Networks and Learning Systems}, 
  
  title={Difficult Novel Class Detection in Semisupervised Streaming Data}, 
  
  year={2023},
  
  volume={34},
  
  number={10},
  
  pages={6872--6886},
  
  doi={10.1109/TNNLS.2022.3213682}
 }
 
 Abstract: Streaming data mining can be applied in many practical applications, such as social media, market analysis,
 and sensor networks. Most previous efforts assume that all training instances except for the novel class have been 
 completely labeled for novel class detection in streaming data. However, a more realistic situation is that only 
 a few instances in the data stream are labeled. In addition, most existing algorithms are potentially dependent 
 on the strong cohesion between known classes or the greater separation between novel class and known classes in 
 the feature space. Unfortunately, this potential dependence is usually not an inherent characteristic of streaming 
 data. Therefore, to classify data streams and detect novel classes, the proposed algorithm should satisfy: 1) it 
 can handle any degree of separation between novel class and known classes (both easy and difficult novel class 
 detection) and 2) it can use limited labeled instances to build algorithm models. In this article, we tackle these 
 issues by a new framework called semisupervised streaming learning for difficult novel class detection (SSLDN), 
 which consists of three major components: an effective novel class detector based on random trees, a classifier 
 by using the information of nearest neighbors, and an efficient updating process. Empirical studies on several 
 datasets validate that SSLDN can accurately handle different degrees of separation between the novel and known 
 classes in semisupervised streaming data.
