# Waste Management Segregation Using CNN ♻️🌱

Welcome to the **Waste Management Segregation** project! This repository contains a machine learning model built using Convolutional Neural Networks (CNN) to automate the classification of waste into two categories: **Organic** 🌱 and **Recyclable** ♻️. This project aims to enhance the efficiency of waste management processes by leveraging image classification.

---
## 📋 Table of Contents

1. [Project Description](#project-description)
2. [Requirements](#requirements)
3. [Week 1 Overview](#week-1-overview)
4. [How to Run the Project](#how-to-run-the-project)
5. [Class Distribution](#class-distribution)
6. [License](#license)

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

## 📊 Class Distribution
Here’s a quick look at the distribution of Organic and Recyclable waste in the dataset:

![Image](https://github.com/user-attachments/assets/2897e6b9-5943-49fa-a3f1-89b90c0ff121)
*Dark Green: Organic 🌱, Light Blue: Recyclable ♻️*

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

## 📝 Project Status
This project is currently in progress. Week 1 tasks have been completed, and further improvements will be made in subsequent weeks, such as fine-tuning the model, adding validation, and increasing dataset size.

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🤖 Contributions

Feel free to fork this repository, make contributions, or create issues for improvements. Let's work together to improve waste segregation systems worldwide! 🌍♻️
```

## 🔗 Links
- [GitHub Profile](https://github.com/shailisahu283)
```
