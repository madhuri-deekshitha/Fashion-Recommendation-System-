# Fashion Recommendation System 👗🤖

A machine learning-based recommendation system that provides visually similar fashion item suggestions using image input. Built using deep learning models and optimized for accuracy, scalability, and user experience.

## 📌 Project Overview

The system allows users to upload images of fashion items (e.g., shirts, dresses) and receive recommendations for visually similar items. It uses pre-trained CNN models for feature extraction and cosine similarity for matching.

## 📸 Features

- Upload fashion item images
- Get top 5 visually similar fashion recommendations
- Utilizes deep learning models: ResNet50, VGG16, InceptionV3, EfficientNetB0
- Image preprocessing and feature extraction
- User-friendly interface

## 🧠 Models Used

| Model         | Accuracy | Precision | Recall | F1-Score |
|---------------|----------|-----------|--------|----------|
| ResNet50      | 65%      | 50%       | 80%    | 55%      |
| VGG16         | 54%      | 80%       | 80%    | 60%      |
| InceptionV3   | 45%      | 30%       | 50%    | 65%      |
| EfficientNetB0| 75%      | 50%       | 50%    | 50%      |

> **EfficientNetB0** showed the best overall performance.

## 🛠️ Tech Stack

- **Frontend**: HTML/CSS/JS (for uploading and displaying results)
- **Backend**: Python, Flask
- **Libraries**: TensorFlow, OpenCV, NumPy
- **Models**: ResNet50, VGG16, InceptionV3, EfficientNetB0

## 🧪 Dataset

The dataset used in this project can be downloaded from the link below:

➡️ [Download Images_Dataset](https://drive.google.com/file/d/1QXe-x_RQ5NXvRmVn2u23XOVhh-0mgh6i/view?usp=sharing).

Please note: The dataset is hosted on Google Drive due to size limits on GitHub.

- **Size**: 44,441 images
- **Categories**: Dresses, shirts, pants, accessories
- **Split**: 70% training, 15% validation, 15% testing
- Preprocessed to 224x224 resolution, normalized, and augmented

## ⚙️ How It Works

1. **Upload Image**: User uploads a fashion item image.
2. **Preprocessing**: Image is resized and normalized.
3. **Feature Extraction**: Image is passed through CNN models to generate a feature vector.
4. **Similarity Matching**: Cosine similarity is used to find the top 5 similar items.
5. **Display Recommendations**: Recommendations are shown with item details and similarity scores.

## 🚀 Future Scope

- Integrate user preferences for personalized results
- Support real-time image processing
- Expand dataset and categories
- Include text-based inputs (e.g., brand, occasion)
- Deploy as a web application with e-commerce integration

## 📚 References

- [Keras](https://keras.io)
- [TensorFlow](https://www.tensorflow.org)
- [PyTorch](https://pytorch.org)
- [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist)

