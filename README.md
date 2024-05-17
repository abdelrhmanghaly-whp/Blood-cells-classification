# Blood Cell Classification with CNN

This repository contains a project that classifies blood cells using convolutional neural networks (CNNs) with TensorFlow and Keras. The project includes three different models: a custom CNN, a VGG16-based model, and a ResNet50-based model. The dataset is used Kaggle.
You can browse the Kaggle Notebook from <b><a href="https://www.kaggle.com/code/abdelrhmanghaly/blood-cancer-classification">here</a></b>


## Installation

To get started, clone this repository

```bash
git clone https://github.com/yourusername/blood-cell-classification.git
cd blood-cell-classification
```


## Model Comparison

In this project, three different CNN models were evaluated: VGG16, a custom CNN, and ResNet50. Here are the results:

- **VGG16**: This model achieved the best performance, almost overfitting with 99% accuracy. The VGG16 model, pre-trained on ImageNet, provides a robust feature extraction mechanism, making it highly effective for this classification task.

- **Custom CNN**: The custom CNN model performed well, achieving 90% accuracy. This model was specifically designed for the blood cell classification task, striking a balance between complexity and performance.

- **ResNet50**: The ResNet50 model achieved 87% accuracy. Despite being a powerful deep learning model known for handling deep networks effectively, it did not perform as well as the VGG16 or the custom CNN in this particular task.

Each model has its strengths and weaknesses, with VGG16 providing the highest accuracy, followed by the custom CNN, and finally, the ResNet50.

The classes for classification are: 'Cancer', 'erythroblast', 'ig', 'lymphocyte', 'neutrophil', and 'platelet'.

Each model has its strengths and weaknesses, with VGG16 providing the highest accuracy, followed by the custom CNN, and finally, the ResNet50.

