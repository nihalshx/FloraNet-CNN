# FloraNet-CNN-Based-Plant-Species-Classifier

FloraNet-CNN is a project aimed at accurately classifying plant species using Convolutional Neural Networks (CNNs). This application is particularly useful for agricultural and environmental purposes, helping to identify black nightshade, cotton, tomato, and velvetleaf plants.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Training the Model](#training-the-model)
- [Evaluation](#evaluation)
- [Prediction](#prediction)
- [Results](#results)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/plant-species-detection.git
    cd plant-species-detection
    ```

2. Set up the environment:
    - If using Colab, mount Google Drive:
        ```python
        from google.colab import drive
        drive.mount('/content/drive')
        ```
    - Install required libraries:
        ```bash
        pip install tensorflow matplotlib
        ```

## Dataset

The dataset used in this project is stored in Google Drive and consists of images categorized into the following folders:
- black_nightsade
- cotton
- tomato
- velvet_leaf

The dataset path is: `/content/drive/MyDrive/early-crop-weed-master/early-crop-weed-master`

## Training the Model

1. **Data preprocessing**: Load and preprocess the dataset.
   
2. **Model architecture**: Define the CNN model using TensorFlow and Keras.

3. **Training**: Compile and train the model on the dataset.

## Evaluation

1. **Performance metrics**: Evaluate the model's accuracy and loss on the training and validation sets.
   
2. **Visualization**: Plot training history (accuracy/loss curves).

## Prediction

1. **Inference**: Load test images and make predictions using the trained model.

## Results

- Achieved accuracy of `XX%` on the training set and `YY%` on the validation set after `ZZ` epochs.
- Displayed predictions for test images with confidence scores.

## License

This project is licensed under the MIT License.
