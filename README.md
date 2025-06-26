# Breast Tumor Detection using Trigonometric Convolutions

📌 Overview :

This project focuses on detecting benign and malignant breast tumors from mammogram images using a convolutional neural network (CNN) enhanced by a custom TrigConv2D layer. The model is designed to identify subtle texture and density patterns commonly observed in breast cancer diagnostics.

⚙️ Key Features :

TrigConv2D Layer : Incorporates sine and cosine transformations into the convolutional layer to enhance the network’s ability to detect micro-textures and irregular structures typical in breast tumors.

Binary Classification : Distinguishes between benign and malignant tumor classes from grayscale mammogram images.

Clean CNN Architecture : Lightweight, end-to-end pipeline for image preprocessing, model training, and validation.

Flexible Data Loader : Supports nested folders for real-world datasets with thousands of mammograms in varying formats.

🧪 Tech Stack :

Python 3, TensorFlow/Keras

OpenCV for grayscale image processing

Trigonometric feature transformation

Metrics: Accuracy, Binary Cross-Entropy, Confusion Matrix


📂 Folder Structure :
markdown

Copy

Edit

DRIVE/

└── breast/

    ├── benign/  
    
    └── malignant/
    
📊 Results : 

The model efficiently learns to differentiate tumor types with minimal preprocessing, demonstrating potential for use in early breast cancer screening tools and medical AI research.
