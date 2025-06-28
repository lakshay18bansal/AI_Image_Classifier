# AI Image Classifier

A binary image classifier to detect whether an image is **real** or **AI-generated** using a custom CNN built in Keras.

---

##  Dataset

- **CIFAKE DATASET.zip** is included in this repo
- Contains two classes: `REAL` and `FAKE`
- All images are resized to 64×64 RGB

---

##  Model Overview

- Built using TensorFlow/Keras
- Architecture:
  - Convolutional layers
  - BatchNormalization
  - Dropout
  - Dense layers with SELU activation
- Saved model: `model_1.keras`

---

##  Files Included

```
AI_Image_Classifier/
│
├── AI_image_classifier.ipynb   # Training script
├── Model_evaluate.ipynb        # Evaluation & predictions
├── CIFAKE DATASET.zip          # Complete dataset (train/test)
├── model_1.keras               # Trained model
├── README.md                   # Project info (this file)
```

---

##  How to Use

1. Unzip the dataset:
   ```bash
   unzip CIFAKE\ DATASET.zip
   ```



2. Open and run the notebooks: 
   - `AI_image_classifier.ipynb` to train
   - `Model_evaluate.ipynb` to test the model

---

