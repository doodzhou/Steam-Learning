
@article{zhou2023robust,

  title={Robust semi-supervised clustering via data transductive warping},
  
  author={Zhou, Peng and Wang, Ni and Zhao, Shu and Zhang, Yanping},
  
  journal={Applied Intelligence},
  
  volume={53},
  
  number={2},
  
  pages={1254--1270},
  
  year={2023},
  
  publisher={Springer}
  
}

Abstract
In practical applications, we are more likely to face semi-supervised data with a small amount of independent class label or constraint information and many unlabeled instances. For semi-supervised clustering, taking advantage of the small portion of preliminary label information can significantly improve the discriminability of representations. Spectral clustering has the benefits of handling any shape data distribution and converging to the optimal global solution but is susceptible to noisy data. However, it is inevitable to contain noise for real-world applications that significantly reduce clustering performance. Motivated by this, we propose a novel Robust Semi-supervised Spectral Clustering method (named RSSC) to address clustering on noise semi-supervised datasets. Specifically, in terms of data transductive warping, we map the entire semi-supervised dataset into a new data space where labeled data is close to the canonical coordinate system, and unlabeled data with similar characteristics should be close to those labeled data. The noise data is close to the origin of the coordinate and form the noise cluster because there is no guidance. Finally, samples in the same cluster are close, and different clusters are separated. Extensive experimental results on sixteen real-world datasets demonstrate that RSSC outperforms other state-of-the-art clustering methods on performance and robustness.
