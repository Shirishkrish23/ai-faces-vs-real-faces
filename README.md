# AI-Generated vs. Real Human Faces Classification

This project aims to differentiate between AI-generated and real human faces using three distinct methods. Each method leverages different image processing and machine learning techniques to identify distinguishing features and accurately classify the images. Below are the details of each method implemented in this project.

## Methods

### Method 1: Convolutional Neural Network (CNN)

The first method involves using a simple 3-layered CNN to classify images. The CNN is trained to identify distinguishing features in the images and classify them as either AI-generated or real human faces.

#### Steps:
1. **Data Preparation**: Load and preprocess the dataset of AI-generated and real human faces.
2. **Model Architecture**: Design a 3-layered CNN.
3. **Training**: Train the CNN on the preprocessed dataset.
4. **Evaluation**: Evaluate the model's performance on a validation set.

### Method 2: Edge Detection and Color Channel Analysis

The second method involves preprocessing images and applying edge detection filters. This helps in identifying distinguishing features based on edge patterns and color channels, providing a visual comparison between the original and processed images.

#### Steps:
1. **Preprocessing**: Apply edge detection filters to the images.
2. **Feature Extraction**: Analyze edge patterns and color channels.
3. **Comparison**: Visually compare the original and processed images to identify distinguishing features.

### Method 3: Frequency Domain Analysis with CNN

The third method utilizes frequency domain analysis coupled with a CNN to classify images based on their unique frequency domain representations. This is achieved through the Discrete Fourier Transform (DFT).

#### Steps:
1. **Frequency Domain Conversion**: Convert images to their frequency domain representations using DFT.
2. **Model Architecture**: Design a CNN to process the frequency domain representations.
3. **Training**: Train the CNN on the frequency domain representations of the dataset.
4. **Evaluation**: Evaluate the model's performance on a validation set.


## Results

The shown results are of the 3rd method
![image](https://github.com/TiredTaurus24/FreqVision/assets/96630810/9de06dbb-2f3c-460b-ab23-781ad7a18141)
![image](https://github.com/TiredTaurus24/FreqVision/assets/96630810/f5678cc6-7d4d-4176-88a7-c0acada6ffab)
![image](https://github.com/TiredTaurus24/FreqVision/assets/96630810/5e3aa14f-ba3b-4a7f-bb86-1d2f62e3b3a1)




## Conclusion

This project demonstrates the versatility of image processing and machine learning techniques in accurately differentiating between AI-generated and real human faces. The complementary strategies provided by the three methods can be applied to various classification tasks involving similar data.

