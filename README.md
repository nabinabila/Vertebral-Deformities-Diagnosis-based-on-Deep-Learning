# Vertebral-Deformities-Diagnosis-based-on-Deep-Learning
The diagnosis of spinal deformities is one of the most frequent daily clinical routine.
X-Ray images are used to diagnose several pathologies in order to reduce harmful radiations of the patient.
Spinal deformities are diagnosed essentially from vertebral shapes, orientations and positions, so their detection and segmentation are major steps required for diagnosis. 
Deep learning could be applied for automatic diagnosis to detect scoliosis and its variants with a favourable performance. In this study, based on 609 spinal anterior-posterior x-ray images obtained from the public SpineWeb (http://spineweb.digitalimaginggroup.ca), we examine Generative Adversarial Network based architectures and Convolutional Neural Networkbased architectures models that are capable of automatically detecting anomalies in radiograph and achieve expert-level performances in various fields providing a solid comparative study.
Most of the implemented models are apt to automatically distinguish limits between vertebrae so determining their shape with a very good visual performance. The GAN-based architecture estimates the required vertebral landmarks with an accuracy rate of 0.966, signify its capacity for automatic scoliosis assessment in a clinical setting.

# Methods
To achieve our objective, we implemented state-of-the-art GANs and CNNs, most famous families in Deep Learning, tailored to the unique challenges of spinal deformity detection. Our approach involved fine-tuning the models using different techniques notably data augmentation techniques to effectively capture the intricate features indicative of various deformity types. This adaptation process was crucial, as existing models were not specifically designed for this mission. We chose GANs for their potential to generate synthetic data, which we anticipated would enhance the models' performance in detecting subtle deformities.
![image (1) (2)](https://github.com/nabinabila/Vertebral-Deformities-Diagnosis-based-on-Deep-Learning/assets/52214161/a5535ca5-ad69-4489-b007-4287f6234268)
# Overview of GAN
Generative Adversarial Networks (GAN) introduced by Goodfellow is considered as one of the most powerful member of the neural network family, due to realistic data generation capacities.
As showen in figure GANs operate by training two competing networks: a generator and a discriminator. The generator produces realistic synthetic samples from noise (the z-latent space), while the discriminator discerns between genuine and synthetic samples. This flexible architecture has been utilized for tasks like identifying the location of vertebrae, discs, and spinal shape.
![unnamed (3)](https://github.com/nabinabila/Vertebral-Deformities-Diagnosis-based-on-Deep-Learning/assets/52214161/03afe3e0-e2bd-46f0-b622-1f67bc4e7683)

# Requirements
The main requirements are listed below:

Tested with Keras 2.3.1

Python 3.6

OpenCV 3.4.2

scikit-image 0.16.2

Numpy

Scikit-Learn

Matplotlib

# Dataset
Dataset provided by:

public SpineWeb (http://spineweb.digitalimaginggroup.ca)

# Results
Visually in figures, the illustration serves as a qualitative showcase of models proficiency in detecting spinal landmarks.
