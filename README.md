## Performance Analysis of Deep Transfer Learning to Classify Skin Cancer Images

This repository contains the code and research paper for the project **"Performance Analysis of Deep Transfer Learning to Classify Skin Cancer Images."** The project focuses on developing and benchmarking advanced AI systems using deep learning convolutional neural networks (CNNs) for accurate classification of skin cancer using high-resolution dermatoscopic images.

## Project Overview
Skin cancer is a significant global health concern, with early diagnosis being critical for effective treatment. This project leverages deep learning techniques to classify skin cancer images efficiently and accurately. The research utilizes the HAM10000 dataset, which includes a diverse set of skin lesions. Various pre-trained CNN models, such as Inception-v3, DenseNet-201, and MobileNetV2, are fine-tuned using transfer learning to enhance the classification performance.

## Key Features
- **Deep Learning Models**: Utilizes state-of-the-art CNN architectures for image classification, including Inception-v3, DenseNet-201, MobileNetV2, and more.
- **Transfer Learning**: Implements transfer learning techniques using pre-trained models from the ImageNet database to improve classification efficiency.
- **Performance Metrics**: Evaluates models using metrics like accuracy, F1 score, precision, and recall, ensuring reliable diagnostic performance.
- **Dataset**: Employs the HAM10000 dataset, consisting of 10,000 dermatoscopic images with seven distinct types of skin lesions.

## Methodology
The research involves training and fine-tuning various CNN models on the HAM10000 dataset using Google Colaboratory's powerful GPUs. Models are implemented using TensorFlow and PyTorch, focusing on key performance metrics to analyze the models' effectiveness in dermatoscopic diagnosis.

## Results
The models achieved significant accuracy in skin cancer classification. DenseNet-201 and ResNet-101 showed high performance, with accuracies exceeding 96% on specific datasets. The findings highlight the potential of AI in assisting dermatologists with more precise and timely diagnostic decisions.
