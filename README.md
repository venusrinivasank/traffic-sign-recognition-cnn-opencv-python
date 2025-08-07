# 🚦 traffic-sign-recognition-cnn-opencv-python
This project is a deep learning-based traffic sign recognition system built using Python (Anaconda), TensorFlow/Keras, OpenCV, and a custom-trained Convolutional Neural Network (CNN). It can identify and classify traffic signs in real time via webcam or on image datasets.

---

## 🧠 Model Highlights
- Built with **Keras + TensorFlow backend**
- Uses a **Convolutional Neural Network (CNN)** with dropout regularization
- Trained on a dataset of 43 traffic sign classes
- Achieves high accuracy with **image preprocessing & augmentation**
- Real-time prediction using webcam

---

## 📦 Requirements

Note:

if you're using anaconda, then anaconda interpretor itself create a virtual environment but if you're using anyother interpretor, make sure to use virtual enviroment to avoid problems during installing the libraries.

Install all the dependencies with:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install numpy pandas opencv-python matplotlib seaborn scikit-learn tensorflow keras
```
---

### 💡 Dataset Info

- The training images are organized into 43 subfolders (0–42), each representing a traffic sign class.
- Label mappings are stored in labels.csv.

```download link:
    https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign
```

---

### 🛠 Tools Used

- Python 🐍 (via Anaconda)
- TensorFlow + Keras
- OpenCV
- Scikit-learn
- Matplotlib & Seaborn
