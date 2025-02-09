# **CNN-Based cat_vs_dog_classifier  **

## **Project Overview**  
This project explores CNN-based image classification using both a custom-built CNN model and transfer learning. The goal is to progressively enhance model accuracy by applying various techniques, such as batch normalization, dropout, data augmentation, and fine-tuning.

## **Dataset**  
- Dataset: [Dogs vs Cats](https://www.kaggle.com/datasets/salader/dogs-vs-cats) from Kaggle  
- Contains images of two categories: **Dogs** and **Cats**
- Used for binary image classification

## **Approach & Notebooks**  
### **1. CNN from Scratch** (`scratch.ipynb`)  
- Built a custom CNN model with **batch normalization** and **dropout** to prevent overfitting.  
- Achieved an initial accuracy of **82.9%**.  

### **2. Transfer Learning – Feature Extraction (Without Data Augmentation)** (`feature_extraction_no_aug.ipynb`)  
- Used **VGG16** as a feature extractor while keeping its convolutional layers frozen.  
- Accuracy improved to **91.02%**, but overfitting was observed.  

### **3. Transfer Learning – Feature Extraction (With Data Augmentation)** (`feature_extraction_aug.ipynb`)  
- Applied **data augmentation** (rotation, flipping, scaling, etc.) to improve generalization.  
- Reduced overfitting and achieved a higher accuracy of **91.62%**.  

### **4. Transfer Learning – Fine-Tuning** (`fine_tuning.ipynb`)  
- Unfroze some deeper layers of **VGG16** and retrained the model to adapt it to the dataset.  
- Achieved the highest accuracy of **X%**.  

## **Results & Observations**  
- Accuracy progressively improved with each approach.  
- Fine-tuning provided the best results, enhancing both accuracy and generalization.  


## **Future Work**  
- Experiment with other pre-trained models (**ResNet, EfficientNet, etc.**).  
- Perform **hyperparameter tuning** for further accuracy improvements.  
- Explore **other augmentation techniques** for better generalization.  

## **Author**  
- **Rohit Kumar**  
- **[Your GitHub Profile](https://github.com/r9hit)**
