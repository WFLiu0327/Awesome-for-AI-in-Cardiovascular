# The Awesome for Artificial Intelligence for Cardiovascular ❤️

In this Awesome project, we will organize and categorize the applications of artificial intelligence in cardiovascular diseases from three perspectives: Tasks (🛠️), Data types (💾), and disease types (🫀).

![homepage_image](https://github.com/WFLiu0327/Awesome-for-AI-in-Cardiovascular/blob/main/imgs/1fc58f96-711b-4247-ae8d-f59dd6cbb9ac.png)

If you have any questions, please feel free to contact me via: WeChat (18810327586) or email (liuweifeng0327@gmail.com).

# **Contents**
* **[Related Reviews](#Reviews) 📝**
<!-- * **[Open-Source Datasets](#Datasets) ** -->
* **[Tasks](#Tasks) 🛠️**
    * [Classification](#classification)
    * [Segmentation](#segmentation)
    * [Reconstruction](#Reconstruction)
    * [Functional Index Calculation](#Calculation)

* **[Data](#Data) 💾**
    * [ECG](#ECG)
    * [CMRI](#CMRI)
    * [CCTA](#ccta)
    * [Electronic Reports](#Electronic-Reports)
    * [Echocardiography](#Echocardiography)
    * [X-ray Imaging](#X-ray-imaging)
    * [Multi-modal Data](#multimodal-data)

* **[Disease](#Disease) 🫀**
    * [Cardiomyopathy](#cardiomyopathy)
    * [Myocardial Infarction](#Myocardial-Infarction)
    * [Coronary Artery Disease](#coronary-artery-disease)
    * [Arrhythmias](#arrhythmias)
    * [Heart Failure](#heart-failure)
    * [Valvular Disease](#valvular-disease)
    * [Congenital Heart Diseases](#congenital-heart-diseases)
    * [Multiple Diseases](#Multiple-Diseases)

# **Reviews 📝**

**Artificial Intelligence: Practical Primer for Clinical Research in Cardiovascular Disease** \
[Sep., 2019] [Journal of the American Heart Association] \
[[Paper](https://www.ahajournals.org/doi/full/10.1161/JAHA.119.012788)] 

**A guide to deep learning in healthcare** \
[Jan., 2019] [Nature Medicine] \
[[Paper](https://www.nature.com/articles/s41591-018-0316-z)]

**Machine Learning-Based Heart Disease Diagnosis: A Systematic Literature Review** \
[Jun., 2022] [Artificial Intelligence in Medicine] \
[[Paper](https://www.sciencedirect.com/science/article/pii/S0933365722000549)] 

**Critical appraisal of artificial intelligence-based prediction models for cardiovascular disease**\
[Aug., 2022] [European Heart Journal] \
[[Paper](https://academic.oup.com/eurheartj/article/43/31/2921/6593474)] 

**Use of Artificial Intelligence in Improving Outcomes in Heart Disease: A Scientific Statement From the American Heart Association**\
[Feb., 2024] [Circulation] \
[[Paper](https://www.ahajournals.org/doi/full/10.1161/CIR.0000000000001201)] 

**Artificial Intelligence in Image-based Cardiovascular Disease Analysis: A Comprehensive Survey and Future Outlook**\
[Feb., 2024] [Arxiv] \
[[Paper](https://arxiv.org/abs/2402.03394)] 

**Multi-modality cardiac image computing: A survey**\
[Aug., 2023] [Medical Image Analysis] \
[[Paper](https://www.sciencedirect.com/science/article/pii/S1361841523001299)] 

**Deep learning in ECG diagnosis: A review**\
[2021] [Knowledge-Based Systems] \
[[Paper](https://doi.org/10.1016/j.knosys.2021.107187)] 

# **Tasks 🛠️**

### Diagnosis 🩺
**Screening and diagnosis of cardiovascular disease using artificial intelligence-enabled cardiac magnetic resonance imaging** \
[May., 2024] [Nature Medicine] \
[[Paper](https://www.nature.com/articles/s41591-024-02971-2)] [[GitHub](https://github.com/MedAI-Vision/CMR-AI)]

**Multi-scale Cross-restoration Framework for Electrocardiogram Anomaly Detection**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2308.01639)] [[GitHub](https://github.com/MediaBrain-SJTU/ECGAD)]

**ProtoASNet: Dynamic Prototypes for Inherently Interpretable and Uncertainty-Aware Aortic Stenosis Classification in Echocardiography**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2307.14433)] [[GitHub](https://github.com/hooman007/ProtoASNet)]

### Segmentation 🖼️
**Correlation-Aware Mutual Learning for Semi-supervised Medical Image Segmentation**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2307.06312)] [[GitHub](https://github.com/Herschel555/CAML)]

**Cross-Adversarial Local Distribution Regularization for Semi-supervised Medical Image Segmentation**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2307.06312)] [[GitHub](https://github.com/PotatoThanh/Cross-adversarial-local-distribution-regularization)]

**Decoupled Consistency for Semi-supervised Medical Image Segmentation**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2307.06312)] [[GitHub](https://github.com/wxfaaaaa/DCNet)]

**Wall Thickness Estimation from Short Axis Ultrasound Images via Temporal Compatible Deformation Learning** \
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_21)] 

**Temporal Uncertainty Localization to Enable Human-in-the-Loop Analysis of Dynamic Contrast-Enhanced Cardiac MRI Datasets**\
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43898-1_44)]

**CorSegRec: A Topology-Preserving Scheme for Extracting Fully-Connected Coronary Arteries from CT Angiography**\
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43898-1_64)] [[GitHub](https://github.com/YH-Qiu/CorSegRec)]

**GL-Fusion: Global-Local Fusion Network for Multi-view Echocardiogram Video Segmentation**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2309.11144)] [[GitHub](https://github.com/xmed-lab/GL-Fusion)]

**Semi-supervised Class Imbalanced Deep Learning for Cardiac MRI Segmentation**\
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43901-8_44)] [[GitHub](https://github.com/IsYuchenYuan/SSCI)]

**CMRVAE: Contrastive margin-restrained variational auto-encoder for class-separated domain adaptation in cardiac segmentation**\
[2024] [Knowledge-Based Systems] \
[[Paper](https://doi.org/10.1016/j.knosys.2024.112412)] 

**A cascaded framework with cross-modality transfer learning for whole heart segmentation**\
[2024] [Pattern Recognition] \
[[Paper](https://doi.org/10.1016/j.patcog.2023.110088)] 

**Robust implementation of foreground extraction and vessel segmentation for X-ray coronary angiography image sequence**\
[2023] [Pattern Recognition] \
[[Paper](https://doi.org/10.1016/j.patcog.2023.109926)]

### Reconstruction 🏗️
**Toward Enabling Cardiac Digital Twins of Myocardial Infarction Using Deep Computational Models for Inverse Inference** \
[Jul., 2024] [IEEE TRANSACTIONS ON MEDICAL IMAGING] \
[[Paper](https://ieeexplore.ieee.org/document/10440104)] [[GitHub](https://github.com/lileitech/MI_inverse_inference)]

**Whole-Heart Reconstruction with Explicit Topology Integrated Learning** \
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_11)] 



### Functional Index Calculation
**Wall Thickness Estimation from Short Axis Ultrasound Images via Temporal Compatible Deformation Learning** \
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_21)] 

**Mitral Regurgitation Quantification from Multi-channel Ultrasound Images via Deep Learning**\
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_22)]

**EchoGLAD: Hierarchical Graph Neural Networks for Left Ventricle Landmark Detection on Echocardiograms**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2307.12229)] [[GitHub](https://github.com/DSL-Lab/echoglad)]

# **Data 💾**

### ECG 💓
**Toward Enabling Cardiac Digital Twins of Myocardial Infarction Using Deep Computational Models for Inverse Inference** \
[Jul., 2024] [IEEE TRANSACTIONS ON MEDICAL IMAGING] \
[[Paper](https://ieeexplore.ieee.org/document/10440104)] [[GitHub](https://github.com/lileitech/MI_inverse_inference)]

**Multi-scale Cross-restoration Framework for Electrocardiogram Anomaly Detection**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2308.01639)] [[GitHub](https://github.com/MediaBrain-SJTU/ECGAD)]

**HQ-DCGAN: Hybrid quantum deep convolutional generative adversarial network approach for ECG generation**\
[2024] [Knowledge-Based Systems] \
[[Paper](https://doi.org/10.1016/j.knosys.2024.112260)] [[GitHub](https://github.com/ErdongChenErdong/HQ-DCGAN)]

**Label decoupling strategy for 12-lead ECG classification**\
[2023] [Knowledge-Based Systems] \
[[Paper](https://doi.org/10.1016/j.knosys.2023.110298)] [[GitHub](https://github.com/Zhangshuojackpot/Label-Decoupling-Module)]

**Artificial intelligence estimated electrocardiographic age as a recurrence predictor after atrial fibrillation catheter ablation**\
[2024] [Nature Medicine] \
[[Paper](https://doi.org/10.1038/s41746-024-01234-1)] 

**Artificial intelligence-enabled prediction of chemotherapy-induced cardiotoxicity from baseline electrocardiograms**\
[2024] [Nature Communications] \
[[Paper](https://doi.org/10.1038/s41467-024-45733-x)]

**An ECG-based artificial intelligence model for assessment of sudden cardiac death risk**\
[2024] [communications medicine] \
[[Paper](https://doi.org/10.1038/s43856-024-00451-9)]

**Machine learning for ECG diagnosis and risk stratification of occlusion myocardial infarction**\
[2023] [Nature Medicine] \
[[Paper](https://doi.org/10.1038/s41591-023-02396-3)]

### CMRI 🧲
**Screening and diagnosis of cardiovascular disease using artificial intelligence-enabled cardiac magnetic resonance imaging** \
[May., 2024] [Nature Medicine] \
[[Paper](https://www.nature.com/articles/s41591-024-02971-2)] [[GitHub](https://github.com/MedAI-Vision/CMR-AI)]

**Correlation-Aware Mutual Learning for Semi-supervised Medical Image Segmentation**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2307.06312)] [[GitHub](https://github.com/Herschel555/CAML)]

**Toward Enabling Cardiac Digital Twins of Myocardial Infarction Using Deep Computational Models for Inverse Inference** \
[Jul., 2024] [IEEE TRANSACTIONS ON MEDICAL IMAGING] \
[[Paper](https://ieeexplore.ieee.org/document/10440104)] [[GitHub](https://github.com/lileitech/MI_inverse_inference)]

**Cross-Adversarial Local Distribution Regularization for Semi-supervised Medical Image Segmentation**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2307.06312)] [[GitHub](https://github.com/PotatoThanh/Cross-adversarial-local-distribution-regularization)]

**Decoupled Consistency for Semi-supervised Medical Image Segmentation**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2307.06312)] [[GitHub](https://github.com/wxfaaaaa/DCNet)]

**Whole-Heart Reconstruction with Explicit Topology Integrated Learning** \
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_11)]

**Temporal Uncertainty Localization to Enable Human-in-the-Loop Analysis of Dynamic Contrast-Enhanced Cardiac MRI Datasets**\
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43898-1_44)]

**Semi-supervised Class Imbalanced Deep Learning for Cardiac MRI Segmentation**\
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43901-8_44)] [[GitHub](https://github.com/IsYuchenYuan/SSCI)]

**CMRVAE: Contrastive margin-restrained variational auto-encoder for class-separated domain adaptation in cardiac segmentation**\
[2024] [Knowledge-Based Systems] \
[[Paper](https://doi.org/10.1016/j.knosys.2024.112412)] 

**A cascaded framework with cross-modality transfer learning for whole heart segmentation**\
[2024] [Pattern Recognition] \
[[Paper](https://doi.org/10.1016/j.patcog.2023.110088)] 

### CCTA
**ImageCAS: A Large-Scale Dataset and Benchmark for Coronary Artery Segmentation based on Computed Tomography Angiography Images**\
[Oct., 2023] [Computerized Medical Imaging and Graphics] \
[[Paper](https://www.sciencedirect.com/science/article/pii/S0895611123001052)] [[GitHub](https://github.com/XiaoweiXu/ImageCAS-A-Large-Scale-Dataset-and-Benchmark-for-Coronary-Artery-Segmentation-based-on-CT)]

**CorSegRec: A Topology-Preserving Scheme for Extracting Fully-Connected Coronary Arteries from CT Angiography**\
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43898-1_64)] [[GitHub](https://github.com/YH-Qiu/CorSegRec)]
### CT
**Whole-Heart Reconstruction with Explicit Topology Integrated Learning** \
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_11)]

**A cascaded framework with cross-modality transfer learning for whole heart segmentation**\
[2024] [Pattern Recognition] \
[[Paper](https://doi.org/10.1016/j.patcog.2023.110088)] 
### Echocardiography
**Wall Thickness Estimation from Short Axis Ultrasound Images via Temporal Compatible Deformation Learning** \
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_21)]

**Mitral Regurgitation Quantification from Multi-channel Ultrasound Images via Deep Learning**\
[2023] [MICCAI] \
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_22)]

**ProtoASNet: Dynamic Prototypes for Inherently Interpretable and Uncertainty-Aware Aortic Stenosis Classification in Echocardiography**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2307.14433)] [[GitHub](https://github.com/hooman007/ProtoASNet)]

**GL-Fusion: Global-Local Fusion Network for Multi-view Echocardiogram Video Segmentation**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2309.11144)] [[GitHub](https://github.com/xmed-lab/GL-Fusion)]

**EchoGLAD: Hierarchical Graph Neural Networks for Left Ventricle Landmark Detection on Echocardiograms**\
[2023] [MICCAI] \
[[Paper](https://arxiv.org/abs/2307.12229)] [[GitHub](https://github.com/DSL-Lab/echoglad)]

### X-Ray
**Robust implementation of foreground extraction and vessel segmentation for X-ray coronary angiography image sequence**\
[2023] [Pattern Recognition] \
[[Paper](https://doi.org/10.1016/j.patcog.2023.109926)] 


# **Disease 🫀**

### Cardiomyopathy 💔
...

### Coronary Artery Disease 🩸
...

### Myocardial Infarction 💥
**Toward Enabling Cardiac Digital Twins of Myocardial Infarction Using Deep Computational Models for Inverse Inference** \
[Jul., 2024] [IEEE TRANSACTIONS ON MEDICAL IMAGING] \
[[Paper](https://ieeexplore.ieee.org/document/10440104)] [[GitHub](https://github.com/lileitech/MI_inverse_inference)]

### Multiple Diseases 🫶
**Screening and diagnosis of cardiovascular disease using artificial intelligence-enabled cardiac magnetic resonance imaging** \
[May., 2024] [Nature Medicine] \
[[Paper](https://www.nature.com/articles/s41591-024-02971-2)] [[GitHub](https://github.com/MedAI-Vision/CMR-AI)]
