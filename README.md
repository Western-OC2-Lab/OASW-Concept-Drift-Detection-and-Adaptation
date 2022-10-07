# OASW-Concept-Drift-Detection-and-Adaptation

This is the code for the paper entitled "**[A Lightweight Concept Drift Detection and Adaptation Framework for IoT Data Streams](https://arxiv.org/pdf/2104.10529.pdf)**" published in **IEEE Internet of Things Magazine**, doi: [10.1109/IOTM.0001.2100012](https://ieeexplore.ieee.org/document/9427288).  
Authors: Li Yang and Abdallah Shami  
Organization: The Optimized Computing and Communications (OC2) Lab, ECE Department, Western University

A complete **tutorial code** for the comprehensive and complete pipeline for **concept drift, online machine learning, and data stream analytics**, including dynamic data pre-processing, drift-based dynamic feature selection, dynamic model learning & selection, and online ensemble models, can be found in: [MSANA-Online-Data-Stream-Analytics-And-Concept-Drift-Adaptation](https://github.com/Western-OC2-Lab/MSANA-Online-Data-Stream-Analytics-And-Concept-Drift-Adaptation)

Another **tutorial code** for **concept drift, online learning, and data stream analytics** can be found in: [PWPAE-Concept-Drift-Detection-and-Adaptation](https://github.com/Western-OC2-Lab/PWPAE-Concept-Drift-Detection-and-Adaptation)

![Alt Text](https://github.com/Western-OC2-Lab/OASW-Concept-Drift-Detection-and-Adaptation/blob/main/real-time_prediction%20with%20drift.gif)

## Abstract
In recent years, with the increasing popularity of “Smart Technology”, the number of Internet of Things (IoT) devices and systems have surged significantly. Various IoT services and functionalities are based on the analytics of IoT streaming data. However, IoT data analytics faces concept drift challenges due to the dynamic nature of IoT systems and the ever-changing patterns of IoT data streams. In this article, we propose an adaptive IoT streaming data analytics framework for anomaly detection use cases based on optimized LightGBM and concept drift adaptation. A novel drift adaptation method named Optimized Adaptive and Sliding Windowing (OASW) is proposed to adapt to the pattern changes of online IoT data streams. Experiments on two public datasets show the high accuracy and efficiency of our proposed adaptive LightGBM model compared against other state-of-the-art approaches. The proposed adaptive LightGBM model can perform continuous learning and drift adaptation on IoT data streams without human intervention.

## Implementation 
### Dataset 
NSL-KDD dataset, a popular network traffic dataset for intrusion detection problems
* Publicly available at: [[1]](https://www.unb.ca/cic/datasets/nsl.html) [[2]](https://github.com/jmnwong/NSL-KDD-Dataset)   

### Code  
* Dataset pre-processing: [1-Data_pre-processing_NSL-KDD.ipynb](https://github.com/Western-OC2-Lab/OASW-Concept-Drift-Detection-and-Adaptation/blob/main/1-Data_pre-processing_NSL-KDD.ipynb)   
* Static machine learning algorithm development: [2-Conventional_or_static_machine_learning_algorithms.ipynb](https://github.com/Western-OC2-Lab/OASW-Concept-Drift-Detection-and-Adaptation/blob/main/2-Conventional_or_static_machine_learning_algorithms.ipynb)   
* Proposed OASW drift detection method implementation: [3-OASW_for_concept_drift_detection&adaptation.ipynb](https://github.com/Western-OC2-Lab/OASW-Concept-Drift-Detection-and-Adaptation/blob/main/3-OASW_for_concept_drift_detection%26adaptation.ipynb)   
* Real-time prediction & drift detection: [4-Real-time_prediction_with_concept_drift_adaptation.ipynb](https://github.com/Western-OC2-Lab/OASW-Concept-Drift-Detection-and-Adaptation/blob/main/4-Real-time_prediction_with_concept_drift_adaptation.ipynb)   
  * [Real-time prediction video](https://github.com/Western-OC2-Lab/OASW-Concept-Drift-Detection-and-Adaptation/blob/main/Real-time_prediction.mp4)

### Requirements & Libraries  
* Python 3.6+
* [scikit-learn](https://scikit-learn.org/stable/)  
* [Xgboost](https://xgboost.readthedocs.io/en/latest/python/python_intro.html)
* [LightGBM](https://lightgbm.readthedocs.io/en/latest/)
* [river](https://riverml.xyz/dev/)
* [hyperopt](https://github.com/hyperopt/hyperopt)  
* [optunity](https://github.com/claesenm/optunity)

## Contact-Info
Please feel free to contact us for any questions or cooperation opportunities. We will be happy to help.
* Email: [liyanghart@gmail.com](mailto:liyanghart@gmail.com) or [Abdallah.Shami@uwo.ca](mailto:Abdallah.Shami@uwo.ca)
* GitHub: [LiYangHart](https://github.com/LiYangHart) and [Western OC2 Lab](https://github.com/Western-OC2-Lab/)
* LinkedIn: [Li Yang](https://www.linkedin.com/in/li-yang-phd-65a190176/)  
* Google Scholar: [Li Yang](https://scholar.google.com.eg/citations?user=XEfM7bIAAAAJ&hl=en) and [OC2 Lab](https://scholar.google.com.eg/citations?user=oiebNboAAAAJ&hl=en)

## Citation
If you find this repository useful in your research, please cite this article as:  

L. Yang and A. Shami, "A Lightweight Concept Drift Detection and Adaptation Framework for IoT Data Streams," in IEEE Internet of Things Magazine, vol. 4, no. 2, pp. 96-101, June 2021, doi: 10.1109/IOTM.0001.2100012.

```
@ARTICLE{9427288,
  author={Yang, Li and Shami, Abdallah},
  journal={IEEE Internet of Things Magazine}, 
  title={A Lightweight Concept Drift Detection and Adaptation Framework for IoT Data Streams}, 
  year={2021},
  volume={4},
  number={2},
  pages={96-101},
  doi={10.1109/IOTM.0001.2100012}}
```
