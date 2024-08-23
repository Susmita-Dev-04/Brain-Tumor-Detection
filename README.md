# Brain-Tumor-Detection
 
OVERVIEW:

This project involves developing a deep learning model to detect the presence of brain tumors from MRI images. The model uses advanced image processing techniques and a binary classification approach to distinguish between MRI images with and without tumors.

TABLE OF CONTENTS:
Overview,
Dataset,
Model Architecture,
Image Preprocessing,
Training,
Evaluation,
Results,
How to Use,
Dependencies,
Future Work


DATASET:
•	Source: Publicly available MRI brain scan datasets on KAGGLE (https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection )
The dataset used in this project consists of MRI images categorized into two classes: with tumor and without tumor. The images were preprocessed to enhance the accuracy of the model.

![image alt](https://github.com/Susmita-Dev-04/Brain-Tumor-Detection/blob/2e679506beafdf700908fbf0dc2fdab172ce9e9e/MRI_images.png)

Model Architecture:
The model is built using a convolutional neural network (CNN) to capture the spatial features of the MRI images. The architecture includes several convolutional layers, max-pooling layers, and fully connected layers to perform binary classification.

![image alt](https://github.com/Susmita-Dev-04/Brain-Tumor-Detection/blob/fc593ba0d82488afdedab0416c22c68fe03fb5b9/Cnn-Architecture.png)

IMAGE PROCESSING:
Image preprocessing steps include resizing, normalization, and data augmentation to increase the robustness of the model. The preprocessing helps in reducing overfitting and improving the generalization of the model.

TRAINING:
The model was trained using the processed dataset. The training involved fine-tuning hyperparameters such as learning rate, batch size, and number of epochs to optimize the model's performance.

EVALUATIONS:
The model's performance was evaluated using metrics such as accuracy, precision, recall, and F1-score. The evaluation was carried out on a separate test set to ensure that the model generalizes well to unseen data.

RESULTS:
The model achieved an accuracy of 84% on the test set, demonstrating its effectiveness in detecting brain tumors from MRI images.

DEPENDENIES:
Python 3.12.5
TensorFlow / Keras
OpenCV
NumPy
Matplotlib

FUTURE WORK:
Improve the model by experimenting with different architectures.
Incorporate a multi-class classification to detect the type of tumor.
Deploy the model as a web application for real-time detection.




