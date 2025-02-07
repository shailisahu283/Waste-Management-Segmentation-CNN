# Waste Management Segregation Using CNN ♻️🌱

Welcome to the **Waste Management Segregation** project! This repository contains a machine learning model built using Convolutional Neural Networks (CNN) to automate the classification of waste into two categories: **Organic** 🌱 and **Recyclable** ♻️. This project aims to enhance the efficiency of waste management processes by leveraging image classification.

---
## 📋 Table of Contents

1. [Project Description](#project-description)
2. [Requirements](#requirements)
3. [Week 1 Overview](#week-1-overview)
4. [Week 2 Overview](#week-2-overview)
5. [Week 3 Overview](#week-3-overview)
6. [How to Run the Project](#how-to-run-the-project)
7. [Class Distribution](#class-distribution)
8. [License](#license)

---
## 📝 Project Description

The **Waste Management Segregation Using CNN** project leverages deep learning, specifically Convolutional Neural Networks (CNNs), to classify images of waste into two main categories: **Organic** 🌱 and **Recyclable** ♻️. The goal of the project is to automate the process of waste classification, which traditionally requires manual sorting, making it more efficient and less prone to human error.

By using a CNN-based model, the system can learn to identify waste categories based on visual patterns, which can then be used to optimize waste disposal and recycling systems in urban areas, industries, and households.

### 🧠 Key Features:
- **Image Classification**: Classifies images into Organic or Recyclable categories.
- **Data Preprocessing**: Converts and normalizes images for use in the CNN.
- **Visualization**: Displays the distribution of waste categories in the dataset.

---

## 🧰 Requirements

To run this project, you’ll need the following libraries and tools:

- Python 3
- TensorFlow (for building the CNN model)
- NumPy (for numerical operations)
- Pandas (for data manipulation)
- Matplotlib (for plotting and visualization)
- OpenCV (for image processing)
- tqdm (for progress bars)
  
---
### Dataset:
You can download the dataset from [here](https://www.kaggle.com/datasets/techsash/waste-classification-data). Make sure to download and extract it to the appropriate directory.

---
### Install Dependencies:
You can install the necessary libraries using pip:

```bash
pip install -r requirements.txt
```

Create a `requirements.txt` file with the following content:

```
tensorflow
numpy
pandas
matplotlib
opencv-python
tqdm
```

## 📅 Week 1 Overview

In Week 1, I focused on setting up the project and implementing the core functionality for data preprocessing, model building, and visualizing the class distribution of the waste dataset.

### 🗂️ What was done:
1. **Data Preprocessing** 🧹:
   - Loaded and preprocessed images from the dataset.
   - Converted images to RGB format.
   - Created data frames to map images with their labels (Organic and Recyclable).
   
2. **Model Building** 🏗️:
   - Defined a simple CNN architecture using TensorFlow/Keras.
   - Added layers such as convolution, pooling, and dense layers for image classification.

3. **Class Distribution Visualization** 📊:
   - Visualized the distribution of Organic vs Recyclable waste in the dataset using a pie chart.
   - Displayed the proportions in a visually appealing manner with a customized color scheme.

---
### 🗓️ **Week 2: Model Training & Improvements**

#### **Improvements**:
- **Data Augmentation**: Implemented techniques like rotation, width and height shifts, zoom, and horizontal flipping to improve model generalization.
- **Learning Rate Scheduler**: Introduced a learning rate scheduler to adjust the learning rate dynamically after a set number of epochs for better training performance.
- **Model Training**: Trained the model for 15 epochs using the augmented data and validated on the test dataset.
- **Visualization**: Plotted accuracy and loss curves to monitor the model’s progress during training and identify any overfitting or underfitting.

---
### **Week 3 Overview**  

- **Fixed Image Loading Issues:** Added error handling to check if the image path is valid before processing.  
- **Resolved OpenCV Conversion Error:** Ensured the image is properly loaded before applying color conversion to prevent crashes.  
- **Optimized Prediction Pipeline:** Refined image resizing, reshaping, and model inference for accurate waste classification.

---

## 📊 Class Distribution
Here’s a quick look at the distribution of Organic and Recyclable waste in the dataset:

![Image](https://github.com/user-attachments/assets/2897e6b9-5943-49fa-a3f1-89b90c0ff121)
*Dark Green: Organic 🌱, Light Blue: Recyclable ♻️*


---

## 💻 Colab Link

You can also run this project on Google Colab for easier setup and execution. Click the link below to open the notebook:

[Open in Google Colab](https://colab.research.google.com/drive/1w1UM2hrvuBcoU9bmH0K09SQYVczZsUXO?usp=sharing)

---

## ⚙️ How to Run the Project
To get started with this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shailisahu283/Waste-Management-Segmentation-CNN.git
   ```
2. **Install dependencies:**
   - Ensure you have Python 3.x installed.
   - Install necessary libraries with pip:
     ```bash
     pip install -r requirements.txt
     ```
3. **Run the code:**
   - Preprocess the data and train the model:
     ```bash
     python week1/data_preprocessing.ipynb
     ```

---

## 📝 **Project Status**

This project is now **completed**. 

- **Week 1**: Completed initial data exploration, visualized class distribution, and began basic model setup.
- **Week 2**: Implemented data augmentation techniques, applied a learning rate scheduler, and trained the model with augmented data. Accuracy and loss plots were generated to monitor training progress.
- **Week 3:**:Finalized the model with improved accuracy. Evaluated it on test data, created a deployment-ready version, and documented the results.
  
**Final Model Performance:**  
- **Training Accuracy:** 82.31%  
- **Validation Accuracy:** 87.62%  
- **Final Loss:** 0.3359  

The model successfully classifies waste images into **Recyclable** and **Organic Waste** categories with high accuracy. Future improvements may include expanding the dataset and fine-tuning with advanced architectures.  

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🤖 Contributions

Feel free to fork this repository, make contributions, or create issues for improvements. Let's work together to improve waste segregation systems worldwide! 🌍♻️
---

## **👤 Author**  
**Shaili Sahu**  
📧 Reach out at [shailisahu283@gmail.com](mailto:shailisahu283@gmail.com) for questions or feedback!  




