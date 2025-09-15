# 🖼️ CNN Image Classification - CIFAR-10

## 📌 Objective
Build a Convolutional Neural Network (CNN) to classify images from the **CIFAR-10 dataset** into 10 categories.

## 📊 Dataset
- CIFAR-10: 60,000 color images (32x32x3) in 10 classes  
- Classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck  

## ⚙️ Implementation Steps
1. Load CIFAR-10 dataset
2. Normalize pixel values
3. Build CNN with Conv2D, MaxPooling2D, Flatten, Dense
4. Train model using Adam optimizer
5. Evaluate with accuracy, loss curves, confusion matrix
6. Save outputs in `screenshots/`

## 📂 Project Structure
```
cnn-image-classification/
 ├── data/
 ├── screenshots/
 ├── cnn_cifar10.ipynb
 ├── README.md
 └── requirements.txt
```

## 🖼️ Sample Outputs
- Accuracy & Loss curves
- Confusion matrix

## 🚀 How to Run
```bash
git clone <your_repo_link>
cd cnn-image-classification
pip install -r requirements.txt
jupyter notebook cnn_cifar10.ipynb
```

## 📈 Results
- CNN achieves ~70% test accuracy after 10 epochs  
- Performance improves with **data augmentation** and more layers  
