# Ensemble-DNNs-for-Alzheimer-s-Disease-Classification-via-Transfer-Learning
This repository implements an ensemble of deep neural networks (DNNs) for the classification of Alzheimer's Disease. The models are trained using transfer learning, leveraging pre-trained architectures for improved performance.


A.	Introduction
We propose a DL-architecture agnostic ensemble strategy for deep neural networks trained through transfer learning. Ensemble learning involves combining predictions of several models to improve overall predictive performance.

B. Objective

• To detect Alzheimer's disease from MRI and PET images.

•	To increase the accuracy of model using transfer learning and ensemble learning.

• To Study and Compare Ensemble Learning model with other classification models.

C. Approach

(1) Data Preprocessing: Resize all the images to (150x150 pixels), Shuffle the order of data samples, split the dataset to train-test sets and One-Hot encoding are the data preprocessing steps done.

(2) Transfer learning: Transfer learning is the improvement of learning in a new task through the transfer of knowledge from a related task that has already been learned.

(3) Ensemble Learning: The ensemble model is a popular approach in machine learning, which combines the predictions of multiple models to achieve better accuracy and generalization. In our study, we used a combination of supervised regression methods to build our ensemble model.


D. Dataset

![image](https://github.com/PranavNahe/Ensemble-DNNs-for-Alzheimer-s-Disease-Classification-via-Transfer-Learning/assets/81244950/0e9b1d5b-e18c-4ba4-a8a0-530c3634b490)


The "Alzheimer's Disease Neuroimaging Initiative" (ADNI) dataset is a well-known dataset used for Alzheimer's disease research and analysis. It contains various types of data, including structural and functional brain imaging, cognitive assessments, and genetic information. Following are some images from dataset of four classes "No Dementia", "Very Mild Dementia", "Mild Dementia" and "Moderate Dementia" respectively


E. Methodology


![image](https://github.com/PranavNahe/Ensemble-DNNs-for-Alzheimer-s-Disease-Classification-via-Transfer-Learning/assets/81244950/928cc1c4-9a12-4f4a-9d5c-68fb13839742)



F. Analysis

The AI/ML project employs a robust combination of transfer learning and ensemble learning techniques to predict Alzheimer's disease, with a diverse set of pre-trained models, including DenseNet, CNN, Efficient NetB7, and VGG19. Transfer learning leverages the knowledge captured by these pre-trained models, allowing the Al system to understand and recognize patterns in medical imaging data more effectively. The models have been fine-tuned to adapt to the specific task of Alzheimer's disease prediction, enhancing their accuracy and performance.
Ensemble learning further boosts the predictive power of the system by combining the outputs of these diverse models. As per the table in results, we can see that the accuracy of our proposed model is highest.


![image](https://github.com/PranavNahe/Ensemble-DNNs-for-Alzheimer-s-Disease-Classification-via-Transfer-Learning/assets/81244950/9bedbb67-18e9-48bb-981b-f13a6b020927)

![image](https://github.com/PranavNahe/Ensemble-DNNs-for-Alzheimer-s-Disease-Classification-via-Transfer-Learning/assets/81244950/2e8a1e10-fa2e-4dd7-a6e7-8dfca91def98)

![image](https://github.com/PranavNahe/Ensemble-DNNs-for-Alzheimer-s-Disease-Classification-via-Transfer-Learning/assets/81244950/162d88d0-3567-4671-b4e4-0e52ecbc47c8)

![image](https://github.com/PranavNahe/Ensemble-DNNs-for-Alzheimer-s-Disease-Classification-via-Transfer-Learning/assets/81244950/d447fc28-b565-4f05-be07-3133929fb2f1)



G. Results

![image](https://github.com/PranavNahe/Ensemble-DNNs-for-Alzheimer-s-Disease-Classification-via-Transfer-Learning/assets/81244950/3b6c5c3b-6529-4e01-b0f1-4a48eac08a4b)



H. Conclusion

This project represents a sophisticated and promising application of AI/ML in the field of medical diagnostics. By incorporating transfer learning and ensemble learning techniques alongside a range of powerful pre-trained models, it showcases a comprehensive and advanced approach to addressing the critical issue of Alzheimer's disease prediction. The combination of transfer learning enables the models to leverage prior knowledge efficiently, improving their understanding of medical images and their ability to recognize disease patterns. Additionally, the ensemble learning approach leverages the strengths of each individual model, leading to a more robust and accurate predictive system.
