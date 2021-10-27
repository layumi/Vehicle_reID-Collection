# Vehicle Re-ID Collection

If you notice any result or the public code that has not been included in this page, please connect [Zhedong Zheng](mailto:zdzheng12@gmail.com) without hesitation to add the method. You are welcomed! 
or create pull request.

Priorities are given to papers whose codes are published.

## Code 
🏎️. The 1st Place Submission to AICity Challenge 2021 nlp re-id track (CVPR 2021 workshop) [[code]](https://github.com/ShuaiBai623/AIC2021-T5-CLV)[[paper]](https://github.com/layumi/NLP-AICity2021/blob/main/doc/CVPRW2021_NLP_AICity.pdf)

🚙: The 2nd Place Submission to AICity Challenge 2021 re-id track (CVPR 2021 workshop) [[code]](https://github.com/Xuanmeng-Zhang/AICITY2021-Track2)

:red_car:  The 1st Place Submission to AICity Challenge 2020 re-id track (CVPR 2020 workshop) [[code]](https://github.com/layumi/AICIty-reID-2020)
 [[paper]](https://github.com/layumi/AICIty-reID-2020/blob/master/paper.pdf)
 
 :helicopter:  Drone-based building re-id (ACM Multimedia 2020) [[code]](https://github.com/layumi/University1652-Baseline)  [[paper]](https://arxiv.org/abs/2002.12186)
 
 GPU-based Fast Re-Ranking [[code]](https://github.com/layumi/Person_reID_baseline_pytorch/tree/master/GPU-Re-Ranking) [[paper]](https://arxiv.org/abs/2012.07620v2)

## Dataset
1. VeRi-776

    [project](https://github.com/VehicleReId/VeRidataset) [paper](https://link.springer.com/chapter/10.1007/978-3-319-46475-6_53)

49,357 images of 776 vehicles from 20 cameras. Like Market-1501 protocol.

The VeRi dataset is divided into a training subset containing 37,781 images of 576 subjects and a testing subset with 13,257 images of 200 subjects.then a query set containing 1,678 images of 200 subjects and a gallery including 11,579 image of 200 subjects are finally obtained.

2. PKU Vehicle-ID

    [project](https://pkuml.org/resources/pku-vehicleid.html) [pdf](http://openaccess.thecvf.com/content_cvpr_2016/papers/Liu_Deep_Relative_Distance_CVPR_2016_paper.pdf)

221,763 images of 2,627 vehicles. Only two camera views??

3. PKU-VD

    [project](https://pkuml.org/resources/pku-vds.html) [pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Yan_Exploiting_Multi-Grain_Ranking_ICCV_2017_paper.pdf)

with attribute.

4. VehicleReID

    [project](https://medusa.fit.vutbr.cz/traffic/research-topics/detection-of-vehicles-and-datasets/vehicle-re-identification-for-automatic-video-traffic-surveillance-ats-cvpr-2016/) [pdf](http://openaccess.thecvf.com/content_cvpr_2016_workshops/w25/papers/Zapletal_Vehicle_Re-Identification_for_CVPR_2016_paper.pdf)

47,123 images from two cameras & lablled on pair.

5. PKU-Vehicle

    [project](http://59.110.216.11/html/) [paper](https://ieeexplore.ieee.org/abstract/document/8265213)

no ID lablled.

6. CompCars

    [project](http://mmlab.ie.cuhk.edu.hk/datasets/comp_cars/index.html) [pdf](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Yang_A_Large-Scale_Car_2015_CVPR_paper.pdf) 

136,726 + 27,618 images of 1,716 cars with attributes. After crop,  136,713.

7. StanfordCars

    [project](http://ai.stanford.edu/~jkrause/cars/car_dataset.html) [pdf](http://ai.stanford.edu/~jkrause/papers/3drr13.pdf)

16,185 images of 196 classes.

8. Vehicle-1M

    [project](http://www.nlpr.ia.ac.cn/iva/homepage/jqwang/Vehicle1M.htm) [pdf](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16206/16270)
    
    
9. VERI-Wild 

[project](https://github.com/PKU-IMRE/VERI-Wild)


## Recent Papers
### **2021**
1. TransReID: Transformer-based Object Re-Identification **(ICCV)** 
[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/He_TransReID_Transformer-Based_Object_Re-Identification_ICCV_2021_paper.pdf) 
[code](https://github.com/damo-cv/TransReID)

2. Viewpoint and Scale Consistency Reinforcement for UAV Vehicle Re-Identification **(IJCV)** 
[pdf](https://link.springer.com/content/pdf/10.1007/s11263-020-01402-2.pdf)

3. Exploring Spatial Significance via Hybrid Pyramidal Graph Network for Vehicle Re-Identification **(TITS)** 
[paper](https://ieeexplore.ieee.org/abstract/document/9457192)

4. PhD Learning: Learning With Pompeiu-Hausdorff Distances for Video-Based Vehicle Re-Identification **(CVPR)** 
[paper](http://openaccess.thecvf.com//content/CVPR2021/html/Zhao_PhD_Learning_Learning_With_Pompeiu-Hausdorff_Distances_for_Video-Based_Vehicle_Re-Identification_CVPR_2021_paper.html) 
[code](https://github.com/emdata-ailab/PhD-Learning)

5. Heterogeneous Relational Complement for Vehicle Re-identification **(ICCV)** 
[paper](https://openaccess.thecvf.com/content/ICCV2021/html/Zhao_Heterogeneous_Relational_Complement_for_Vehicle_Re-Identification_ICCV_2021_paper.html) 
[code](https://github.com/iCVTEAM/HRCN)

6. Model Latent Views With Multi-Center Metric Learning for Vehicle Re-Identification **(TITS)** 
[paper](https://ieeexplore.ieee.org/document/9325909/)

7. Inter-Domain Adaptation Label for Data Augmentation in Vehicle Re-identification **(TMM)** 
[paper](https://ieeexplore.ieee.org/abstract/document/9513554)

8. Learning Multiple Semantic Knowledge For Cross-Domain Unsupervised Vehicle Re-Identification **(ICME)** 
[paper](https://ieeexplore.ieee.org/abstract/document/9428440)

9. Multi-level Deep Learning Vehicle Re-identification using Ranked-based Loss Functions **(ICPR)** 
[paper](https://ieeexplore.ieee.org/abstract/document/9412415)

10. Keypoint-Aligned Embeddings for Image Retrieval and Re-Identification **(WACV)** 
[pdf](https://openaccess.thecvf.com/content/WACV2021/papers/Moskvyak_Keypoint-Aligned_Embeddings_for_Image_Retrieval_and_Re-Identification_WACV_2021_paper.pdf)

11. Pseudo Graph Convolutional Network for Vehicle ReID **(ACMMM)** 
[paper](https://dl.acm.org/doi/abs/10.1145/3474085.3475462)

12. Vehicle Re-identification for Lane-level Travel Time Estimations on Congested Urban Road Networks Using Video Images **(TITS)** 
[paper](https://ieeexplore.ieee.org/abstract/document/9569748)

13. OERFF: A Vehicle Re-Identification Method Based on Orientation Estimation and Regional Feature Fusion **(IEEE Access)** 
[paper](https://ieeexplore.ieee.org/abstract/document/9416706)

14. Counterfactual Attention Learning for Fine-Grained Visual Categorization and Re-identification **(ICCV)** 
[arXiv](https://arxiv.org/abs/2108.08728) 
[code](https://github.com/raoyongming/CAL)

15. Self-Supervised Geometric Features Discovery via Interpretable Attention for Vehicle Re-Identification and Beyond **(ICCV)** 
[pdf](https://openaccess.thecvf.com/content/ICCV2021/papers/Li_Self-Supervised_Geometric_Features_Discovery_via_Interpretable_Attention_for_Vehicle_Re-Identification_ICCV_2021_paper.pdf)

### **2020**
1. VehicleNet: Learning Robust Visual Representation for Vehicle Re-identification **(TMM)**
[arXiv](https://arxiv.org/abs/2004.06305) 
[[中文介绍]](https://zhuanlan.zhihu.com/p/186905783)

2. Beyond the Parts: Learning Multi-view Cross-part Correlation for Vehicle Re-identification **(ACM MM)** 
[paper](http://xinchenliu.com/papers/2020_ACMMM_PCRNet.pdf) 
[code](https://github.com/lxc86739795/parsing_platform)

3. The Devil is in the Details: Self-Supervised Attention for Vehicle Re-Identification **(ECCV)** 
[arXiv](https://arxiv.org/abs/2004.06271) 
[[中文介绍]](https://zhuanlan.zhihu.com/p/191654655)

4. Structural Analysis of Attributes for Vehicle Re-Identification and Retrieval **(TITS)** 
[paper](https://ieeexplore.ieee.org/document/8643580)

5. Group-Group Loss-Based Global-Regional Feature Learning for Vehicle Re-Identification **(TIP)** 
[paper](https://ieeexplore.ieee.org/document/8897720) 
[code](https://github.com/liu-xb/GGL)

6. Simulating Content Consistent Vehicle Datasets with Attribute Descent **(ECCV)** 
[pdf](https://link.springer.com/content/pdf/10.1007/978-3-030-58539-6_46.pdf) 
[code](https://github.com/yorkeyao/VehicleX)
[[中文介绍]](https://zhuanlan.zhihu.com/p/198061566)

7. Parsing-based View-aware Embedding Network for Vehicle Re-Identification **(CVPR)** 
[paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Meng_Parsing-Based_View-Aware_Embedding_Network_for_Vehicle_Re-Identification_CVPR_2020_paper.html)
[code](https://github.com/silverbulletmdc/PVEN)
[[中文介绍]](https://zhuanlan.zhihu.com/p/160877803)

8. Robust Re-Identification by Multiple Views Knowledge Distillation **(ECCV)** [paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/996_ECCV_2020_paper.php) 
[code](https://github.com/aimagelab/VKD)

9. Orientation-aware Vehicle Re-identification with Semantics-guided Part Attention Network **(ECCV)** 
[pdf](https://paperswithcode.com/paper/orientation-aware-vehicle-re-identification) 
[code](https://github.com/tsaishien-chen/SPAN)

10. Vehicle Re-Identification Using Quadruple Directional Deep Learning Features **(TITS)** 
[paper](https://ieeexplore.ieee.org/document/8667847)

11. Multi-Spectral Vehicle Re-Identification: A Challenge **(AAAI)** 
[paper](https://ojs.aaai.org//index.php/AAAI/article/view/6796)

12. Unsupervised Vehicle Re-identification with Progressive Adaptation **(IJCAI)** 
[paper](https://www.ijcai.org/proceedings/2020/127)

13. Disentangled Feature Learning Network for Vehicle Re-Identification **(IJCAI)** 
[paper](https://www.ijcai.org/proceedings/2020/66)

14. CFVMNet: A Multi-branch Network for Vehicle Re-identification Based on Common Field of View **(ACMMM)** 
[paper](https://dl.acm.org/doi/10.1145/3394171.3413541)

15. A Structured Graph Attention Network for Vehicle Re-Identification **(ACMMM)** 
[paper](https://dl.acm.org/doi/10.1145/3394171.3413607)

16. Fine-grained Feature Alignment with Part Perspective Transformation for Vehicle ReID **(ACMMM)** 
[paper](https://dl.acm.org/doi/abs/10.1145/3394171.3413573)

17. Background Segmentation for Vehicle Re-identification **(MMM)** 
[paper](https://link.springer.com/chapter/10.1007/978-3-030-37734-2_8)

18. Dual Domain Multi-Task Model for Vehicle Re-Identification **(TITS)** 
[paper](https://ieeexplore.ieee.org/abstract/document/9226133/)

19. Multi-View Spatial Attention Embedding for Vehicle Re-Identification **(TCSVT)** 
[paper](https://ieeexplore.ieee.org/abstract/document/9033992)

20. Unsupervised domain adaptive re-identification: Theory and practice **(PR)** 
[paper](https://www.sciencedirect.com/science/article/pii/S003132031930473X)

21. VARID: Viewpoint-Aware Re-IDentification of Vehicle Based on Triplet Loss **(TITS)** 
[paper](https://ieeexplore.ieee.org/abstract/document/9210535)

22. Uncertainty-Aware Multi-Shot Knowledge Distillation for Image-Based Object Re-Identification **(AAAI)** 
[paper](https://ojs.aaai.org/index.php/AAAI/article/view/6774)

23. Tell The Truth From The Front: Anti-Disguise Vehicle Re-Identification **(ICME)** 
[paper](https://ieeexplore.ieee.org/abstract/document/9102939)

24. Vehicle Re-Identification Using Distance-Based Global and Partial Multi-Regional Feature Learning **(TITS)** 
[paper](https://ieeexplore.ieee.org/abstract/document/8972901)

### **2019**
1. VR-PROUD: Vehicle Re-identification using PROgressive Unsupervised Deep architecture **(PR)** [paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320319300147)

2. Embedding Adversarial Learning for Vehicle Re-Identification **(TIP)** [paper](https://ieeexplore.ieee.org/abstract/document/8653852)

3. Vehicle Re-Identification Using Quadruple Directional Deep Learning Features **(TITS)** [pdf](https://arxiv.org/pdf/1811.05163.pdf)

4. VehicleNet: Learning Robust Feature Representation for Vehicle Re-identification **（CVPR workshop）** [paper](http://openaccess.thecvf.com/content_CVPRW_2019/html/AI_City/Zheng_VehicleNet_Learning_Robust_Feature_Representation_for_Vehicle_Re-identification_CVPRW_2019_paper.html)

5. Part-regularized Near-duplicate Vehicle Re-identification **(CVPR)** [pdf](http://cvteam.net/papers/2019_CVPR_Part-regularized%20Near-duplicate%20Vehicle%20Re-identification.pdf)

### **2018**
1. Viewpoint-aware Attentive Multi-view Inference for Vehicle Re-identification **(CVPR)** [pdf](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhou_Viewpoint-Aware_Attentive_Multi-View_CVPR_2018_paper.pdf)

2. Unsupervised Vehicle Re-Identification using Triplet Networks **(CVPR workshop)** [pdf](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w3/Marin-Reyes_Unsupervised_Vehicle_Re-Identification_CVPR_2018_paper.pdf)

3. Vehicle Re-Identification with the Space-Time Prior **(CVPR workshop)** [pdf](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w3/Wu_Vehicle_Re-Identification_With_CVPR_2018_paper.pdf)

4. Fast vehicle identification via ranked semantic sampling based embedding **(IJCAI)** [pdf](https://www.ijcai.org/proceedings/2018/0514.pdf)

5. Vehicle re-identification by deep hidden multi-view inference **(TIP)** [paper](https://ieeexplore.ieee.org/abstract/document/8325486)

6. Ram: a region-aware deep model for vehicle re-identification **(ICME)** [pdf](https://arxiv.org/pdf/1806.09283.pdf)

7. Learning Coarse-to-Fine Structured Feature Embedding for Vehicle Re-Identification **(AAAI)** [pdf](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewFile/16206/16270)

8. PROVID- Progressive and Multimodal Vehicle Reidentification for Large-Scale Urban Surveillance **(TMM)** [paper](https://ieeexplore.ieee.org/abstract/document/8036238)

9. Group Sensitive Triplet Embedding for Vehicle Re-identification **(TMM)** [paper](https://ieeexplore.ieee.org/abstract/document/8265213)

10. VP-ReID: vehicle and person re-identification system **(ACMMM)** [paper](https://dl.acm.org/citation.cfm?id=3206086)

11. Vehicle Re-Identification by Adversarial Bi-Directional LSTM Network **(WACV)** [paper](https://ieeexplore.ieee.org/abstract/document/8354181/)

12. Joint Semi-supervised Learning and Re-ranking for Vehicle Re-identification **(ICPR)** [paper](https://ieeexplore.ieee.org/abstract/document/8545584/)

13. Multi-Attribute Driven Vehicle Re-Identification with Spatial-Temporal Re-Ranking **(ICIP)** [paper](https://ieeexplore.ieee.org/abstract/document/8451776/)

14. Joint feature and similarity deep learning for vehicle re-identification **(IEEE Access)** [paper](https://ieeexplore.ieee.org/abstract/document/8424333/)
### **2017**
1. Orientation Invariant Feature Embedding and Spatial Temporal Regularization for Vehicle Re-Identification **(ICCV)** [pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Wang_Orientation_Invariant_Feature_ICCV_2017_paper.pdf)

2. Learning Deep Neural Networks for Vehicle Re-ID With Visual-Spatio-Temporal Path Proposals **(ICCV)** [pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Shen_Learning_Deep_Neural_ICCV_2017_paper.pdf)

3. Exploiting Multi-Grain Ranking Constraints for Precisely Searching Visually-similar Vehicles **(ICCV)** [pdf](http://openaccess.thecvf.com/content_ICCV_2017/papers/Yan_Exploiting_Multi-Grain_Ranking_ICCV_2017_paper.pdf)

4. Improving triplet-wise training of convolutional neural network for vehicle re-identification **(ICME)** [paper](https://ieeexplore.ieee.org/abstract/document/8019491)

5. Deep hashing with multi-task learning for large-scale instance-level vehicle search **(ICME workshop)** [paper](https://ieeexplore.ieee.org/abstract/document/8026274)

6. Multi-modal metric learning for vehicle re-identification in traffic surveillance environment **(ICIP)** [paper](https://ieeexplore.ieee.org/abstract/document/8296683)

7. Vehicle re-identification by fusing multiple deep neural networks **(IPTA)** [paper](https://ieeexplore.ieee.org/abstract/document/8310090)
 
8. Beyond human-level license plate super-resolution with progressive vehicle search and domain priori GAN **(ACMMM)** [paper](https://dl.acm.org/citation.cfm?id=3123422)
### **2016**
1. Vehicle Re-Identification for Automatic Video Traffic Surveillance **(CVPR workshop)** [pdf](http://openaccess.thecvf.com/content_cvpr_2016_workshops/w25/papers/Zapletal_Vehicle_Re-Identification_for_CVPR_2016_paper.pdf)

2. Deep Relative Distance Learning- Tell the Difference Between Similar Vehicles **(CVPR)** [pdf](http://openaccess.thecvf.com/content_cvpr_2016/papers/Liu_Deep_Relative_Distance_CVPR_2016_paper.pdf)

3. A Deep Learning-Based Approach to Progressive Vehicle Re-identification for Urban Surveillance **(ECCV)** [paper](https://link.springer.com/chapter/10.1007/978-3-319-46475-6_53)

4. Large-Scale Vehicle Re-Identification in Urban Surveillance Videos **(ICME)** [pdf](https://www.researchgate.net/profile/Xinchen_Liu/publication/303760492_Large-scale_vehicle_re-identification_in_urban_surveillance_videos/links/59e424090f7e9b97fbeb0ded/Large-scale-vehicle-re-identification-in-urban-surveillance-videos.pdf)

### Reference
- https://github.com/bismex/Awesome-vehicle-re-identification
- https://github.com/knwng/awesome-vehicle-re-identification
