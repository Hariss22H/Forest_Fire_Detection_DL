# 🔥 Forest Fire Detection using Deep Learning

This project uses Convolutional Neural Networks (CNN) to automatically detect forest fires from images. It's designed to help in early fire detection, potentially aiding in disaster prevention and environmental protection.

## 📌 Project Highlights

- 🌲 Image classification of **forest fire** vs **normal forest**.
- 🧠 Deep Learning model built using **Keras** and **TensorFlow**.
- 📊 Model training and evaluation with **accuracy and loss curves**.
- 🖼️ Real-time prediction on custom test images.
- 📁 Organized dataset with image preprocessing and augmentation.

## 📂 Folder Structure
```bash
Forest_Fire_Detection_Project/
├── Updated_Forest_Fire_Detection.ipynb      # Jupyter Notebook (main code)
├── Dataset/
│   ├── Training/
│   │   ├── forest/                          # Images with forest fire (training)
│   │   └── not_forest/                      # Images without fire (training)
│   └── Testing/
│       ├── forest/                          # Images with forest fire (testing)
│       └── not_forest/                      # Images without fire (testing)


```
## 🧪 Model Architecture

- Input Layer
- 3 Convolution + MaxPooling layers
- Flatten layer
- Dense layer (ReLU)
- Output layer (Sigmoid for binary classification)

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/forest-fire-detection.git
   cd forest-fire-detection
   pip install -r requirements.txt
---

## 📈 Results
Achieved high accuracy on the validation dataset.

Visualized training/validation loss and accuracy.

Classified custom images with proper output labels.

## 🔧 Requirements
Python 3.x

TensorFlow / Keras

Matplotlib

NumPy

OpenCV

Jupyter Notebook

All required libraries are included in the notebook.


## ✨ Future Work
🔭 Integrate real-time camera feeds.

📱 Build a mobile/web app for live forest monitoring.

🛰️ Use satellite data for large-scale fire tracking.


## 🤝 Contributing
Feel free to fork this repo and submit pull requests to improve the model, UI, or add new features!


