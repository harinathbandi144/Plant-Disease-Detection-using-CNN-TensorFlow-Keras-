# Plant-Disease-Detection-using-CNN-TensorFlow-Keras-
CNN-based plant disease detection system using TensorFlow and Keras. Trained on PlantVillage dataset to classify plant leaf diseases with high accuracy and confidence prediction. Includes preprocessing, training, and model versioning.

# 🌿 Plant Disease Detection using CNN

This project is an end-to-end deep learning solution for detecting plant leaf diseases from images using Convolutional Neural Networks (CNN). The model is trained on the PlantVillage dataset and can classify different types of plant diseases with high accuracy.

## 🚀 Features
- Image classification using CNN (TensorFlow & Keras)
- Data preprocessing and augmentation
- Train, validation, and test dataset pipeline
- Model training with accuracy tracking
- Prediction system with confidence score
- Model versioning and saving

## 🧠 Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Matplotlib
- OpenCV / PIL (for image processing)

## 📊 Dataset
- PlantVillage Dataset (publicly available)
- Contains labeled images of healthy and diseased plant leaves

## ⚙️ Workflow
1. Data loading using `image_dataset_from_directory`
2. Dataset splitting (train, validation, test)
3. Data preprocessing (resizing, rescaling, augmentation)
4. CNN model building
5. Model training and evaluation
6. Prediction and visualization
7. Model saving with version control

## 📈 Results
- Achieved high accuracy on validation dataset
- Model can predict disease type with confidence score

## 🔮 Future Improvements
- Deploy as a web app (Streamlit / Flask)
- Add real-time prediction using camera
- Improve model with transfer learning (ResNet, MobileNet)
- Expand dataset for more crops

## 📌 Usage
Clone the repo and run the training script:

```bash
git clone <your-repo-link>
cd plant-disease-detection
pip install -r requirements.txt
python train.py