# Image Classifier for Sumthing.org

## Introduction

Welcome to the Image Classifier project! This Jupyter Notebook details a machine learning solution developed for Sumthing.org. The NGO, dedicated to environmental conservation, needed a tool to automatically sort batches of images into two categories: 'trees' and 'plastic'. This classification aids in documenting and showcasing their efforts in tree planting and garbage collection to donors and the public.

## Project Objective

- **Aim**: To develop an automated image classifier for efficiently sorting images into 'trees' and 'plastic'.
- **Benefit**: Streamlines image management and enhances the presentation of the NGO's environmental initiatives.

## Approach

- **Method**: Utilized TensorFlow and Keras to build a neural network, adopting the MobileNetV2 model with transfer learning.
- **Outcome**: Achieved a remarkable 100% accuracy in image classification, showcasing the model's efficiency and reliability.

## Application

- The classifier processes images sourced from local storage or AWS S3 buckets.
- Post-classification, the images are sorted into designated folders on AWS S3, simplifying access and documentation.

## Impact

- The model significantly aids in managing large image datasets.
- Provides a visual record of the NGO's impactful work, boosting transparency and donor engagement.

 ## Data Collection

- **Technique**: In addition to the existing image dataset, I extended the data collection process through web scraping.
- **Tools Used**: Utilized Python libraries like BeautifulSoup and Selenium to gather images from various online sources.
- **Purpose**: This effort enriched the dataset, providing a broader range of images for training and enhancing the classifier's robustness.
"""

## Conclusion

This project exemplifies the application of machine learning in environmental conservation, offering a practical solution to a real-world challenge faced by Sumthing.org.


Feel free to explore the code and reach out for any queries or collaborations on similar projects!
