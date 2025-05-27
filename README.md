# AI-for-Health-Detecting-Tuberculosis-from-Chest-X-rays-
I built a Convolutional Neural Network (CNN) that classifies chest X-rays as Normal or TB-infected.

## 📊 Dataset

**Source**: Montgomery County Chest X-ray Set, provided by the National Library of Medicine (NIH).

- **Normal X-rays**: 80 images  
- **TB X-rays**: 58 images  
- **Image Format**: PNG (12-bit grayscale)  
- **Original Resolution**: 4020×4892 or 4892×4020  
- **Preprocessed Resolution**: 256×256 RGB

## 🛠️ Technologies Used

- Python 🐍
- TensorFlow & Keras 🧠
- NumPy, Pandas, Matplotlib 📊
- OpenCV (for image handling)
- scikit-learn (metrics, train/test split)


🔍 What I Did:

- Preprocessed high-resolution grayscale images and resized them to 256×256 pixels.
- Built a deep CNN with multiple convolutional and max-pooling layers.
- Achieved 100% test accuracy (validated using stratified 80:20 split).
- Used binary_crossentropy loss and the Adam optimizer for binary classification.
- Visualized training progress using Matplotlib.

📈 Results:

✅ Test Accuracy: 100.00%
✅ Precision, Recall, F1-score: 1.0
✅ Robust detection of TB vs Normal with zero false positives/negatives on the test set.

💡 Tools & Tech: Python, TensorFlow/Keras, OpenCV, Matplotlib, Scikit-learn

🔜 Next Steps:

- Apply transfer learning using pre-trained models like ResNet or VGG.
- Experiment with Grad-CAM for X-ray heatmap visualization.
- Convert the model to ONNX and deploy it in a mobile app.

