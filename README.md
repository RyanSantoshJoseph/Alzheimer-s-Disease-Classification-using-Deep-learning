Alzheimer's disease (AD) is a progressive neurodegenerative disorder primarily affecting older adults, characterized by cognitive decline, memory impairment, and reduced quality of life. The early and accurate detection of Alzheimer's disease is crucial, as it enables timely intervention, which can improve patient outcomes and slow disease progression. Traditional diagnostic methods, though effective, often require extensive clinical evaluations and can be both time-consuming and costly. To address this, recent advancements in artificial intelligence, specifically Convolutional Neural Networks (CNNs), have shown promise in analysing neuroimaging data for automated Alzheimer’s detection.
This study explores the application of CNNs to accurately classify brain MRI images, differentiating between healthy and Alzheimer's-affected brains. Using a dataset developed in the UCS 1603 Introduction to Machine Learning Course, which includes 6,400 images categorized into four levels of cognitive impairment, our approach leverages CNN architectures optimized for extracting intricate features from neuroimaging data. The methodology encompasses essential stages such as data pre-processing, model architecture selection, training, and validation. Techniques like data augmentation and transfer learning are applied to improve model robustness and enhance classification accuracy.
The proposed CNN model achieved an accuracy of 89.65%, an F1 score of 0.8938, and demonstrated high sensitivity and specificity across different classes. These results highlight the model’s potential for reliable early-stage detection of Alzheimer’s disease, positioning it as a viable diagnostic tool for integration into healthcare systems. Our research not only contributes to machine learning and medical imaging but also underscores the significance of AI-driven diagnostics in advancing healthcare accessibility and effectiveness for Alzheimer's patients.



I.	INTRODUCTION
A.	Background
Alzheimer’s disease (AD) is a chronic neurodegenerative disorder affecting millions of individuals worldwide, especially among the elderly population. It is characterized by progressive memory loss, cognitive decline, and functional impairment, eventually leading to a loss of independence. The primary pathological features include the accumulation of amyloid plaques and tau tangles in the brain, resulting in neuronal death and brain atrophy. As the global population ages, the prevalence of Alzheimer’s disease is expected to rise, posing a significant social and economic burden.

B.	Importance of Early Diagnosis
Timely diagnosis of Alzheimer’s disease can play a critical role in managing its progression. Early intervention enables better treatment planning, potentially slowing the progression of symptoms and improving the patient’s quality of life. However, traditional diagnostic approaches, such as cognitive testing and clinical evaluations, are often time-consuming and may not identify the disease until it is well-advanced. Neuroimaging techniques like Magnetic Resonance Imaging (MRI) have emerged as effective tools for detecting structural brain changes associated with AD, providing a window for early detection. Still, manual analysis of MRI data can be both labour-intensive and prone to human error.


C.	Role of Artificial Intelligence in Medical Diagnostics
Advancements in artificial intelligence (AI), particularly in deep learning, have provided new opportunities for automated disease detection. Convolutional Neural Networks (CNNs), a class of deep learning models specifically designed for image analysis, have shown great promise in medical imaging. By automatically extracting relevant features from images, CNNs can perform complex pattern recognition tasks, reducing the need for manual intervention. In recent years, CNNs have achieved remarkable success in various medical imaging applications, such as cancer detection, cardiovascular disease prediction, and diabetic retinopathy screening, making them a compelling choice for Alzheimer’s detection.

D.	Objectives of the Study
This study aims to design, implement, and evaluate a CNN-based model to detect Alzheimer’s disease using MRI brain images. The objectives of this research are as follows:
•	Develop a CNN model that can classify MRI images into different categories based on the presence and severity of Alzheimer’s.
•	Utilize data pre-processing techniques to enhance the quality and consistency of the dataset, ensuring better model performance.
•	Leverage transfer learning and other optimization techniques to improve the accuracy and generalizability of the model.
•	Quantify model performance using metrics such as accuracy, sensitivity, specificity, and F1 score, and assess the model’s potential for practical application in clinical settings.
E.	Scope and Contribution of the Study
This research presents a systematic approach to developing an AI-driven diagnostic model that addresses the challenges associated with Alzheimer’s disease detection. By utilizing CNNs, this study aims to:
•	Improve diagnostic accuracy through automated feature extraction and analysis of MRI images.
•	Contribute to the growing field of AI-driven healthcare solutions, particularly for neurodegenerative diseases.
•	Lay the groundwork for future research in expanding and refining deep learning models for neuroimaging.

