# publications
A curated index of my academic publications, conference papers, and research outputs in Artificial Intelligence and Machine Learning.

# Academic Publications

**Abhay Varun S**  
Artificial Intelligence and Machine Learning | Computer Vision | Deep Learning

Welcome to my academic publications repository. This repository provides a centralized index of my research papers, conference publications, and associated research resources.

## Research Interests

- Computer Vision and Image Segmentation
- Deep Learning
- Artificial Intelligence and Machine Learning
- Agricultural AI and Intelligent Systems

## Publications

### 1. CoffeeBeanSeg: A Polygon-Annotated Instance Segmentation and Quality Grading Dataset with YOLOv11 Benchmarking

- Authors: Samruddh K; Abhay Varun S; Bopanna K. N; H. A. Dheemanth Gowda
- Venue: ICCIDS 2026
- Year: 2026
- Status: Published
- Paper:https://ieeexplore.ieee.org/document/11407544/authors#authors
- DOI: 10.1109/ICCIDS69108.2026.11407544
- Dataset:https://huggingface.co/datasets/SamruddhK/coffee-bean-grading-dataset%7D

- Abstract:
  This work focuses on the clear and efficient assessment of pre-roast coffee bean quality in the global agricultural supply chain. This task faces significant challenges. While computer vision is a scalable method, progress has been limited owing to the general rarity of specialist public datasets. Most              current collections tend to focus more on coarse classification rather than the fine-grained localization necessary for automated sorting. To fill this gap, we present a new, publicly available dataset of 3,877 high-resolution images of raw beans of Coorg origin. Manual classification of these beans was done by     local experts into four quality grades: A- Premium, B- Good, C-Standard, and D- Defective. The main contribution of the paper is the subset of 2,284 images with careful annotation of their exact polygon masks and grade labels, thereby allowing advanced instance segmentation model development. Data acquisition was   done under controlled lighting with multiple consumer-grade devices to ensure practical relevance of results. We outline a comprehensive protocol for data collection and verify the quality of the dataset by establishing a strong baseline using a state-of-the-art YOLOv11 model. This dataset is designed to support    research in automated agricultural grading and to help create models that can perform object detection, segmentation, and classification at the same time.



### 2. Chromato-Textural Profiling for Unroasted Robusta Coffee Bean Grading: An Interpretable Framework via Chaos Game Optimization and XGBoost

- Authors: K. Samruddh, S. Abhay Varun, K. C. Harshith, G. Parikshith Uthappa, M. J. Prekshith & K. N. Bopanna 
- Venue: ComSIA 2026
- Year: 2026
- Status: Published 
- Paper:https://link.springer.com/chapter/10.1007/978-3-032-30960-0_6
- DOI:https://doi.org/10.1007/978-3-032-30960-0_6

- Abstract:
  This work addresses the assessment of coffee bean quality, which is a major determinant of market value. Admittedly, traditional manual grading is a labor-intensive, subjective process that is prone to inconsistencies. In this respect, we propose a robust and interpretable computer-vision framework for grading      Robusta coffee beans in the context of precision agriculture. Using a purposefully curated dataset containing 3,859 high-resolution images from the Coorg region of India, a two-stage processing pipeline was developed: First, a YOLOv11m-seg model was used solely for ROI extraction by attaining a segmentation mean    Average Precision (mAP@50) of 0.995, thus ensuring the precise elimination of beans from the background noise. Then, the extraction of an extensive 48-dimensional feature vector was performed that characterized the CIELAB color statistics along with textural descriptors of LBP, GLCM, Gabor, and morphological        shape characteristics. To eliminate redundant features without jeopardizing interpretability and, at the same time enhance the computational efficiency of our pipeline, a hybrid classifier architecture has been proposed which integrates Chaos Game Optimization (CGO) using Optuna with an XGBoost classifier. The      metaheuristic optimization offered by CGO efficiently reduced the feature space into a compact subset of 30 discriminative features. Empirical results indicate the superiority of the proposed CGO–XGBoost framework in classification with a testing accuracy of 93.61% and an F1-score of 0.9359, outperforming the       baseline ensemble methods and conventional evolutionary optimization strategies such as Genetic Algorithms. These empirical findings thus indicate that the proposed methodology offers a scalable low-latency, explainable solution that can easily be deployed on edge computing devices in agricultural fields and        industrial sorting lines.

### 3. Low-Shot and Few-Shot Learning for Automated Coffee Bean Grading: Benchmarking CNNs and Transformers

- Authors: K. Samruddh, S. Abhay Varun & M. J. Prekshith 
- Venue: ComSIA 2026
- Year: 2026
- Status: Published 
- Paper:https://link.springer.com/chapter/10.1007/978-3-032-31170-2_32
- DOI:https://doi.org/10.1007/978-3-032-31170-2_32

- Abstract:
  The task of automatic grading of pre-roast coffee beans is greatly hampered by the lack of availability of quality datasets. We introduce a publicly available dataset of 3,859 labeled Robusta coffee beans, divided into four categories of quality. A custom YOLOv11m-seg framework is used to obtain standardized        Region of Interest (ROI) crops for classification. Using the framework, we compare the performance of seven architectures ResNet-50, EfficientNet-B3, and Vision Transformer models (ViT, Swin, DeiT, BEiT) on zero-shot, few-shot (k = 10, 20), and low-shot (k = 100, 200) learning settings, where k represents the       number of training examples per class. Our results demonstrate that the Transformer models are more data-efficient in low-data settings. Specifically, ViT-Base shows the best unsupervised feature separability, and Swin-Large achieves the best accuracy on few-shot learning. Interestingly, a performance crossover     is observed as the amount of training data increases, and the CNN-based ResNet-50 becomes highly competitive on the low-shot setting (k = 200), outperforming several Transformer models. Our results also demonstrate that the Transformers focus on defect-level details, which are consistent with expert grading,        whereas CNNs focus on textural features. These results support the idea that Transformers are superior in low-data settings, but CNNs are also competitive as data availability increases. Our dataset and benchmark offer a strong starting point for future research in data-efficient agricultural computer vision.



## Author Profiles

- **GitHub:** https://github.com/abhay-error
- **ORCID:** https://orcid.org/0009-0003-1299-724X
- **LinkedIn:** https://www.linkedin.com/in/abhay-varun-s-05a06438

## Citation and Reuse

Please cite each publication using its official bibliographic record or DOI. Refer to the applicable publisher, conference, or repository license for permissions to reuse the paper, dataset, and associated materials.

---

This repository is maintained to provide a consolidated, accessible record of my research.
