# Image Recognition: Cats vs. Dogs using OpenCV and SVM

## Overview
This project implements an image recognition system to classify images of cats and dogs using **OpenCV** for image processing and **Support Vector Machine (SVM)** for classification. **Histogram of Oriented Gradients (HOG) feature extraction** is used to improve accuracy.

## Features
- Loads and preprocesses images using OpenCV
- Extracts features using HOG for better accuracy
- Trains an SVM model for classification
- Classifies new images as either a cat or a dog

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install numpy opencv-python scikit-learn matplotlib
```

## Dataset
You can use the **Kaggle Cats vs Dogs dataset** or any dataset with labeled images of cats and dogs. Place images in the following structure:

```
project_folder/
    ├── data/
    │   ├── cat/
    │   │   ├── cat1.jpg
    │   │   ├── cat2.jpg
    │   │   ├── ...
    │   ├── dog/
    │   │   ├── dog1.jpg
    │   │   ├── dog2.jpg
    │   │   ├── ...
```

## Implementation
The project follows these steps:
1. **Load and Preprocess Images**: Images are converted to grayscale and resized for consistency.
2. **Feature Extraction using HOG**: HOG is applied to extract meaningful features from the images, improving classification accuracy.
3. **Train the SVM Model**: An SVM classifier with a linear kernel is trained on the extracted features.
4. **Prediction on New Images**: The trained model is used to classify new images as either a cat or a dog.

## Results
By using **HOG feature extraction**, the model achieves **higher accuracy** compared to basic feature extraction techniques. The final accuracy depends on dataset quality and hyperparameter tuning.

## Future Improvements
- Experiment with deep learning models like CNNs for even better accuracy.
- Tune SVM hyperparameters for optimal performance.
- Explore additional feature extraction methods for further improvements.

## License
This project is open-source and free to use for educational purposes.

---
**Happy Coding! 🚀**

