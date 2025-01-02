
# CSC 509 -- Data Science and Machine Learning for Medical Image Analysis

This GitHub repository contains the notebooks we will go over for CSC509. 

# Course overview

Number of Credits: 3

Course Level: Junior and senior undergraduates

Description: The interpretation of medical images is a major bottleneck in medicine. Traditionally, medical experts must train for years or decades to become proficient in distinguishing abnormalities such as lesions or cancerous growths from normal tissue. Nevertheless, expert radiologists often disagree in their interpretation of such images, resulting in delayed or erroneous diagnoses or uncertain measurements of disease progression. This course explores the application of state-of-the-art deep learning models to biomedical image analysis: the task of identifying objects such as features within an image and classifying images according to disease type. The course introduces key medical imaging technologies and data types, begins with an overview of topics central to medical image analysis and deep learning based image analysis and culminates in two hands-on case studies.

Course objectives:
1. Learn the fundamentals of biomedical imaging with focus on different imaging technologies and their applications in clinical practice and in clinical research. Students should be made cognizant of current challenges and some ways that machine learning can address them.

2. Learn how to apply machine learning tools to classify images and identify disease subtypes.



# Module 0: Introduction to medical imaging and deep learning applications
**Learning objectives**
* Understand the basic principles of medical images
	* How medical imaging is used in clinical practice and clinical trials
	* Basics of different imaging technologies
	* Example cases for disease diagnosis, prognosis and trial endpoints  
* Understand why deep learning is useful for medical imaging problems
	* What kinds of problems are we currently using deep learning for in medical imaging? (e.g. diagnosis, prognosis, segmentation, automatic labeling and image retrieval, quantifying change) 
* Understand the unique challenges in applying DL to medical images


### Module 0, Notebook 1: Introduction to Medical Imaging Formats
Goal: Understand 2 commonly used medical image formats (dicom, nifti) and visualize medical images
<br> 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/spring-2025/Module0/2_04_2025_Module0_Notebook1_DataCuration.ipynb) 

### Module 0, Notebook 2: Classification of PET vs MRI 

Goal: Reinforce the basics of convolutional neural network via PET vs MRI simple classifier development in Keras <br> 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/spring-2025/Module0/2_13_2025_Module0_Notebook2_SimpleClassification.ipynb) 

# Module 1: Alzheimer’s disease classification

### Module 1, Notebook 1: Data Processing for ADNI MRI 
Goal: Learn how to navigate the data processing pipeline. Get familiar with a deep learning dataset and what it looks like. <br> 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/spring-2025/Module1/02_18_2025_Module1_NB1_ADNI_Dataset.ipynb)

### Module 1, Notebook 2: AD classification deep learning notebook 
Goal: Build a classifier that actually solves a real data problem. <br> 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/spring-2025/Module1/02_20_2025_Module1_NB2_ADNI_ADClassification.ipynb)

### Module 1, Notebook 3: Implementing regularization techniques in Keras models
Goal: Understand the ways to code regularization into neural nets. Understand how it impacts training. <br> 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/spring-2025/Module1/02_27_2025_Module1_NB3_Regularization.ipynb)

# Module 2: Brain tumor segmentation 
### Module 2, Notebook 1: BraTS data processing
Goal: Get familiar with the Nifti file format and understand what kinds of data you're working with; how to manipulate it: <br> 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/spring_2024/Module2/03_07_2024_Module2_NB1_BraTS_DataProcessing.ipynb)
### Notebook 2: Brain tumor segmentation 
Goal: Learn how to build a deep learning segmentation algorithm in Keras. <br> 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/spring-2025/Module2/03_13_2025_Module2_NB2_BraTS_TumorSegmentation.ipynb)
