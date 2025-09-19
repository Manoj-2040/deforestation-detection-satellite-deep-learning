# 🌍 Deforestation Identification through Satellite Images using Deep Learning

## 📌 Project Overview

This project focuses on detecting deforestation regions using **satellite images** and **Deep Learning models**. With deforestation being one of the leading contributors to climate change, forest degradation, and biodiversity loss, this project aims to provide an AI-powered solution to identify and monitor deforested areas accurately.

---

## 🎯 Objectives

* Develop a **Deep Learning-based classification system** for detecting deforestation.
* Experiment with multiple neural network architectures including **CNN, SELU, TANH, and VGG16**.
* Evaluate performance metrics such as **accuracy, precision, recall, and F1-score**.
* Provide a scalable solution that can be integrated into real-world monitoring systems.

---

## 🛠️ Technologies Used

* **Programming Language:** Python 🐍
* **Deep Learning Frameworks:** TensorFlow, Keras
* **Libraries:** NumPy, Pandas, Matplotlib, Seaborn, scikit-learn
* **Model Architectures:** CNN, SELU, TANH, VGG16
* **Dataset:** Satellite imagery dataset for forest cover classification

---

## 📂 Repository Structure

```
├── DL_MINI_selu.ipynb          # Model using SELU activation
├── DL_MiniProject.ipynb        # Base CNN model implementation
├── DL_MiniProject_tanh.ipynb   # Model using TANH activation
├── DL_VGG16.ipynb              # Transfer Learning with VGG16
├── README.md                   # Project documentation
```

---

## 🚀 Implementation Steps

1. **Data Preprocessing:**

   * Load and clean satellite images.
   * Apply resizing, normalization, and augmentation.

2. **Model Development:**

   * Build CNN-based models with different activation functions (SELU, TANH).
   * Implement **VGG16** for transfer learning.

3. **Training & Evaluation:**

   * Train models on dataset.
   * Evaluate performance using accuracy and confusion matrix.

4. **Comparison of Models:**

   * Compare CNN variants with VGG16.
   * Identify the best-performing architecture.

---

## 📊 Results

* Achieved **\~90% accuracy** in detecting deforestation regions.
* **VGG16 outperformed** other models due to transfer learning from ImageNet.
* SELU and TANH models showed competitive performance but slightly lower than VGG16.

---

## 🌱 Impact

This project demonstrates how **AI and Deep Learning** can be used to tackle environmental issues like deforestation. With further improvements, it can be deployed for:

* Government monitoring systems.
* Environmental NGOs.
* Research in climate change and biodiversity.

---

## 📖 Future Enhancements

* Expand dataset with high-resolution multi-spectral images.
* Use advanced architectures like **ResNet, EfficientNet**.
* Deploy model as a **web-based application** for real-time monitoring.

---

## 📜 License

This project is licensed under the **MIT License**.

---

⭐ If you found this project helpful, don’t forget to **star the repository**!
