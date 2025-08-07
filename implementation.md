### 🧪 Step-by-Step Project Setup
✅ Step 1: Install Required Libraries<br>
📥 Install libraries like TensorFlow, Keras, OpenCV, etc.

```bash
pip install -r requirements.txt
```

### ✅ Step 2: Import Libraries
📚 Load necessary packages in your Model.ipynb.

### ✅ Step 3: Load and Preprocess Dataset
📂 Load images from the Train and Test folders.<br>
📊 Normalize, grayscale, equalize, and reshape images.

### ✅ Step 4: Define CNN Model
🧠 Build the CNN architecture with Conv2D, MaxPooling, Dropout, Flatten, and Dense layers.

### ✅ Step 5: Train the Model
🏋️‍♂️ Train the model with augmented image data for 30 epochs.

### ✅ Step 6: Evaluate the Model
🧾 View metrics like:

- Accuracy
- Loss
- Confusion Matrix
- Classification Report

### ✅ Step 7: Save the Trained Model
💾 Export the model to trained_model.h5.

### ✅ Step 8: Real-Time Detection (Camera.ipynb)
🎥 Use webcam input and classify live traffic signs with probability display.

---

### 📷 How to Use Webcam Prediction

1. Run Camera.ipynb
2. Hold up a printed traffic sign or use your phone
3. Model will detect and show:
- Class ID
- Class name
- Prediction probability

Press q to quit the webcam window.

---

### 📊 Performance

- ✅ Accuracy: ~X% (replace with your actual)
- 📉 Loss: ~Y%
