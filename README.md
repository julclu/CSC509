
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
* Understand the basic principles of medical images (X-ray, CT, PET, MRI, OCT, US) with a focus on: 
	* How medical imaging is used in clinical practice and clinical trials
	* Principles and acquisition basics of different imaging technologies
	* Some example cases for disease diagnosis, prognosis and trial endpoints  
* Understand why deep learning/CNNs are specifically useful for medical imaging problems
	* What kinds of problems are we currently using deep learning for in medical imaging? (e.g. diagnosis, prognosis, segmentation, automatic labeling and image retrieval, quantifying change) 
* Understand the unique challenges in applying CNNs to medical images
* Understand convolutions and how they are uniquely suited to automatic feature extraction with image-based data 


### Notebook 1: Introduction to Medical Imaging Formats
Goal: Understand 2 commonly used medical image formats (dicom, nifti) and visualize medical images  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/main/Module0/Module0_NB1_Intro_Medical_Imaging_Formats.ipynb)

### Notebook 2: Classification of PET vs MRI 
Goal: Reinforce the basics of convolutional neural network via PET vs MRI simple classifier development in Keras 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/main/Module0/Module0_NB2_v0.ipynb)

# Module 1: Alzheimer’s disease classification

### Notebook 1: ADNI data wrangling (PET) 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/main/Module1/Module1_NB1_ADNI_PET_DataWrangling.ipynb)

## Notebook 2: ADNI data wrangling (MRI) 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/main/Module1/Module1_NB2_ADNI_MRI_DataWrangling.ipynb)
## Notebook 3: AD classification deep learning notebook 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/main/Module1/Module1_NB3_ADNI_ADClassification.ipynb)

# Module 2: Brain tumor segmentation 
## Notebook 1: BraTS data processing
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/main/Module2/Module2_NB1_BraTS_DataProcessing.ipynb)
## Notebook 2: Brain tumor segmentation 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/julclu/CSC509/blob/main/Module2/Module2_NB2_BraTS_TumorSegmentation.ipynb)