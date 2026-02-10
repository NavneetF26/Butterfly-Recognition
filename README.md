# Butterfly-Recognition 

### 🦋 Butterfly Recognition System using Convolutional Neural Networks
This project is about building a deep learning model to automatically identify different species of butterflies from images. It uses a Convolutional Neural Network (CNN) built with Python and Keras to classify images into five butterfly species.

---

### 📚 Dataset
The model was trained on a dataset containing **663 images**(Kaggle) from 5 species:

* Cairns Birdwing
* Green Celled Cattleheart
* Monarch
* Paper Kite
* Ulysses

---

### 🎯 Objective
To help researchers and butterfly enthusiasts easily recognize species from images by creating an accurate, automated classification system.

---

### 🛠️ Tools & Technologies
* **Languages:** Python
* **Libraries:** TensorFlow, Keras, NumPy, Matplotlib, OpenCV
* **Development Tools:** Jupyter Notebook, Kaggle (for dataset handling and training)

---

### 🧠 Model Overview
* Built a CNN using Keras with multiple layers to extract and learn image features.
* Trained the model for 10 epochs using the Adam optimizer and a batch size of 32.
* Applied data augmentation and preprocessing to improve performance.

---

### ✅ Results
* **Validation Accuracy:** 99.62%
* **Validation Loss:** 0.0134
* **Test Accuracy on separate data:** 99.62%
* **Practical Evaluation Accuracy (manual test):** 90% (18 correct out of 20)

---

### 🧪 Future Improvements
* Add more butterfly species to the dataset
* Deploy the model as a web or mobile application
* Explore transfer learning for faster and more efficient training
