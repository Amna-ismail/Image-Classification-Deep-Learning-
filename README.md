# Image-Classification-Deep-Learning-
INTRODUCTION:
CIFAR-10 stands for "Canadian Institute For Advanced Research" and the number "10" indicates that the dataset consists of 10 different classes. The goal of this project was to create a deep learning model capable of classifying images into one of ten categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. The dataset used for this task is the CIFAR-10 dataset, which consists of 60,000 32x32 color images. These images are divided into 50,000 training images and 10,000 test images, making it a widely used benchmark for image classification tasks.
DATA PREPROCESSING
1.	Loading the Data: 
2.	Normalization: 
3.	Visualization: 
 
MODEL ARCHITECTURE
A Convolutional Neural Network (CNN) was built using Keras. The model architecture includes several convolutional and pooling layers followed by fully connected (dense) layers. The architecture is as follows:
1.	Convolutional Layer: 32 filters, 3x3 kernel, ReLU activation.
2.	Max Pooling Layer: 2x2 pool size.
3.	Convolutional Layer: 64 filters, 3x3 kernel, ReLU activation.
4.	Max Pooling Layer: 2x2 pool size.
5.	Convolutional Layer: 64 filters, 3x3 kernel, ReLU activation.
6.	Flatten Layer: Converts 3D feature maps to 1D feature vectors.
7.	Dense Layer: 64 units, ReLU activation.
8.	Dense Layer: 10 units (one for each class), no activation (logits output).
 
MODEL TRAINING
MODEL EVALUATION
PREDICTION
 
CONCLUSION
The project successfully demonstrated the creation and training of a CNN for image classification using the CIFAR-10 dataset. The model achieved a reasonable accuracy of approximately 70% on the test dataset. While the performance is decent, there are several ways to improve the model further:
1.	Hyperparameter Tuning: Experimenting with different hyperparameters such as learning rate, batch size, and number of epochs.
2.	Data Augmentation: Using techniques such as rotation, zoom, and horizontal flipping to increase the diversity of the training data.
3.	Advanced Architectures: Employing more sophisticated architectures like ResNet or VGG can potentially improve the performance.
4.	Regularization Techniques: Adding dropout layers or L2 regularization to prevent over fitting.
