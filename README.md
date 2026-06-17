# Plant_Disease_Detection_CNN
Plant leaf disease detection using Computer Vision and Deep Learning with Simple CNN, Hybrid CNN, and Quantum CNN models.
# Kaggle Notebook

Explore the complete implementation and experiments on Kaggle:
https://www.kaggle.com/code/sayamstuti/plant-disease-detection-using-cnn
## Project Description

This project focuses on automated plant leaf disease detection using computer vision and deep learning techniques. Three different architectures—Simple CNN, Hybrid CNN, and Quantum CNN—were implemented and compared to classify plant diseases from leaf images. The project includes image preprocessing, data augmentation, model training, and performance evaluation using metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

The comparative study provides insights into the effectiveness of classical and quantum-inspired neural networks for agricultural applications.

# Working of the Models
1. Simple CNN

The Simple CNN model uses convolutional and pooling layers to automatically extract features such as edges, textures, and shapes from leaf images. These extracted features are then passed through fully connected layers to classify the plant disease.

2. Hybrid CNN

The Hybrid CNN combines classical convolutional neural networks with additional feature extraction or optimization techniques to improve classification performance. This approach enhances the model's ability to capture complex patterns in leaf images.

3. Quantum CNN

The Quantum CNN integrates quantum circuits with classical neural networks. Image features extracted by the CNN are processed using quantum layers, leveraging principles of quantum computing to explore improved learning and classification capabilities.

# Results
## Results

The performance of the three models was evaluated using Accuracy, Precision, Recall, and F1-Score.

| Model                | Accuracy (%) | Precision (%) | Recall (%) | F1-Score (%) |
| -------------------- | -----------: | ------------: | ---------: | -----------: |
| CNN                  |        95.19 |         95.19 |      95.19 |        95.19 |
| Hybrid CNN           |        96.55 |         96.55 |      96.55 |        96.55 |
| Quantum-Inspired CNN |        78.32 |         78.32 |      78.32 |        78.32 |

### Key Observations

* The **Hybrid CNN** achieved the highest performance with an accuracy of **96.55%**.
* The **CNN** model achieved strong classification performance with **95.19%** accuracy.
* The **Quantum-Inspired CNN** achieved **78.32%** accuracy, demonstrating the potential of quantum-inspired approaches while highlighting opportunities for further optimization.
