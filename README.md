# skeleton_action_awesome
Representive papers of our groups for skeleton-based human action understanding

# [Modeling Temporal Dynamics and Spatial Configurations of Actions Using Two-Stream Recurrent Neural Networks](https://github.com/hongsong-wang/skeleton_action_awesome/blob/main/Modeling%20Temporal%20Dynamics%20and%20Spatial%20Configurations%20of%20Actions%20Using%20Two-Stream%20Recurrent%20Neural%20Networks.pdf), CVPR, 2017
This is the first two-stream framework for modeling human temporal dynamics and spatial configurations. The proposed two-stream paradigm has been widely adopted in designing networks for skeleton-based human action recognition in this field, e.g., the two-stream Transformer-based networks.
![Two-stream RNN pipeline](two_stream.jpg)

# [Beyond Joints: Learning Representations From Primitive Geometries for Skeleton-Based Action Recognition and Detection](https://github.com/hongsong-wang/skeleton_action_awesome/blob/main/Beyond_Joints_Learning_Representations_From_Primitive_Geometries_for_Skeleton-Based_Action_Recognition_and_Detection.pdf), TIP, 2018
This is the first work on multimodal skeleton-based human action recognition. We design three modalities from skeleton data—joints, edge, and surface—and find that a simple late fusion of these three streams can significantly improve performance. The widely adopted three modalities, namely joint, bone, and motion, are derived from our work. The bone modality corresponds to our edge modality, and the implementation of the bone also just uses our released code, available at [https://github.com/hongsong-wang/Beyond-Joints](https://github.com/hongsong-wang/Beyond-Joints). 
![Three modalities of human skeletons](edge_face.jpg)

# [Learning content and style: Joint action recognition and person identification from human skeletons](https://github.com/hongsong-wang/skeleton_action_awesome/blob/main/Learning%20content%20and%20style%20Joint%20action%20recognition%20and%20person%20identification%20from%20human%20skeletons.pdf), PR, 2018
This is the first work studies skeleton-based person identification.

# [Occluded Skeleton-Based Human Action Recognition with Dual Inhibition Training](https://github.com/hongsong-wang/skeleton_action_awesome/blob/main/Occluded%20Skeleton-Based%20Human%20Action%20Recognition%20with%20Dual%20Inhibition%20Training.pdf), ACM MM, 2023
This paper addresses occluded and noise-robust skeleton-based action recognition and presents a novel Dual Inhibition Training strategy.
![Part-Aware GCN for occluded skeleton-based representation learning](PDGCN.png)

# [USDRL: Unified Skeleton-Based Dense Representation Learning with Multi-Grained Feature Decorrelation](https://github.com/wengwanjiang/USDRL/tree/main), AAAI, 2025
This paper proposes a unified framework for skeleton-based human action understanding, encompassing action recognition, action retrieval, and action detection.
![unified dense representation learning framework](aaai25.png)

# [Heterogeneous Skeleton-Based Action Representation Learning](https://cvpr.thecvf.com/virtual/2025/poster/32563), CVPR, 2025
This paper is the first work that studies unified skeleton-based human action recognition from heterogeneous skeletons.

```
@inproceedings{wang2017modeling,
  title={Modeling temporal dynamics and spatial configurations of actions using two-stream recurrent neural networks},
  author={Wang, Hongsong and Wang, Liang},
  booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition},
  pages={499--508},
  year={2017}
}

@article{wang2018beyond,
  title={Beyond joints: Learning representations from primitive geometries for skeleton-based action recognition and detection},
  author={Wang, Hongsong and Wang, Liang},
  journal={IEEE Transactions on Image Processing},
  volume={27},
  number={9},
  pages={4382--4394},
  year={2018},
  publisher={IEEE}
}

@article{wang2018learning,
  title={Learning content and style: Joint action recognition and person identification from human skeletons},
  author={Wang, Hongsong and Wang, Liang},
  journal={Pattern Recognition},
  volume={81},
  pages={23--35},
  year={2018},
  publisher={Elsevier}
}
```
