# EyeNet 🧠👁️

**EyeNet** is a deep learning-based project focused on the **early detection of Age-related Macular Degeneration (AMD)** using retinal fundus images. By leveraging **Convolutional Neural Networks (CNNs)** and **transfer learning**, EyeNet offers a reliable and efficient diagnostic tool designed for clinical and real-world applications.

---

## 📂 Project Structure

This repository contains a single Jupyter Notebook:

- `EyeNet_AMD_Detection.ipynb` – The complete notebook that handles:
  - Data loading and preprocessing
  - Model architecture (CNN-based)
  - Transfer learning implementation
  - Model training and evaluation

---

## 📊 Dataset

We use the [ODIR-5K](https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k) dataset provided by **Kaggle**, which includes over 5,000 retinal images labeled with various ocular diseases.

For this project, we focus on **AMD-related classifications** from the multi-label annotations.

---

## 🧠 Model & Methodology

- Implemented a **CNN model** with transfer learning using pre-trained weights (e.g., ResNet, VGG).
- Applied image preprocessing and augmentation for better generalization.
- Used techniques like dropout, batch normalization, and adaptive learning rate.
- Evaluated using accuracy, confusion matrix, and validation loss.

---

## ✅ Results

- Achieved high training and validation accuracy (exact numbers can be updated).
- The model effectively distinguishes AMD-affected images from healthy ones.

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Johnwick-400/EyeNet.git
   cd EyeNet
   ```

2. Open the notebook:
   - Run `EyeNet_AMD_Detection.ipynb` in Jupyter Notebook or Google Colab.
   - Make sure to upload or mount the ODIR-5K dataset before running.

---

## 🔍 Future Improvements

- Add real-time webcam or image upload support for predictions.
- Deploy as a web application for clinical use.
- Expand to detect other ocular diseases in the dataset.

---

## 👨‍💻 Author

- **Veesam Parasuram Pavan Teja**  
  B.Tech Final Year
  Lendi Institute Of Engineering and Technology  
  📧 pavantejveesam26@gmail.com

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).


> “EyeNet aims to make accurate AMD diagnosis accessible and efficient—one retina at a time.”
