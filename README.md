# Scenery Classification Using Convolutional Neural Network Towards Indonesia Tourism

Dataset -> https://github.com/shabrinaiu/Dataset_Indonesia 

## Authors:
- Nana Ramadijanti
- Tita Karlita
- Achmad Basuki
- Ulima Inas Shabrina
- Feri Afrianto
- Andro Aprila Adiputra
- Muhammad Dzalhaqi

## Institution:
Department of Informatics and Computer Engineering, Electronic Engineering Polytechnic Institute of Surabaya, Indonesia

## Overview:
This project aims to promote Indonesia's diverse tourist spots by developing a deep learning-based model for automatic detection and identification of tourist locations from images. Utilizing Convolutional Neural Networks (CNN), the model classifies various tourist attractions to make lesser-known sites more accessible to tourists.

## Problem Statement:
- How to identify tourist spots from photos without descriptions?
- How to promote Indonesia's natural beauty effectively?

## Objectives:
- Develop a deep learning model to identify and classify tourist attractions from images.
- Enhance the visibility of less popular tourist spots through technology.

## Methodology:
1. **Dataset Collection:** A dataset of 4256 images representing 30 classes of tourist attractions was used.
2. **Data Augmentation:** Various augmentations were applied, including horizontal flip, Gaussian blur, and color grading adjustments.
3. **Model Training:** Different CNN architectures, including VGG16 and ResNet, were trained with and without pre-trained weights on datasets like Place365 and ImageNet.

## Results:
- The highest validation accuracy (90%) was achieved using the VGG16 model pre-trained on Place365 with data augmentation.
- Models without data augmentation generally had lower validation accuracies.

## Conclusion:
The CNN-based model shows promising results for classifying Indonesian tourist spots, particularly when using pre-trained models and data augmentation. Future improvements can focus on increasing the model's ability to generalize features from the dataset.

## Contributions:
This project contributes to promoting Indonesia's tourism by leveraging advanced image classification techniques to highlight lesser-known attractions.

## References:
1. N. Ramadhani, J. Hendryli, D. E. Herwindiati, "PENCARIAN OBJEK WISATA BERSEJARAH DI PULAU JAWA MENGGUNAKAN CONVOLUTIONAL NEURAL NETWORK," JURNAL ILMU KOMPUTER DAN SISTEM INFORMASI, Vol. 7 No. 1, 2019.
2. T. Hirotsu, M. Hirota, T. Araki, M. Endo, H. Ishikawa, "Tourism application with CNN-Based Classification specialized for cultural information," Proceedings of the 21st International Conference on Information Integration and Web-based Applications & Services, 2019.
3. Y. E. Ozkose, T. A. Yilikoğlu, L. Karacan, A. Erdem, "Finding Location of A Photograph with Deep Learning," IEEE, 2018.
