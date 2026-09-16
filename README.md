# deep-learning-image-classification
Deep Learning project using TensorFlow and Fashion MNIST to classify fashion product images into 10 categories.
# Deep Learning Fashion Image Classification

## 📌 Project Overview

This project demonstrates a simple **Deep Learning image classification model** using Python, TensorFlow, and the Fashion MNIST dataset.

The model is designed to identify fashion product images and classify them into one of **10 product categories**.

The project connects Deep Learning with a practical **e-commerce business use case**, where AI can assist in automatically categorizing product images.

## 🎯 Objectives

* Understand how images are used as input for Deep Learning.
* Build a simple Artificial Neural Network.
* Understand input, hidden, and output layers.
* Train a model using fashion product images.
* Evaluate model accuracy.
* Predict the category of unseen images.
* Understand the business application of image classification.

## 📊 Dataset

The project uses the **Fashion MNIST dataset** available through TensorFlow/Keras.

The dataset contains grayscale images of fashion products with **10 categories**:

1. T-shirt/Top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle Boot

Each image is **28 × 28 pixels**.

## 🧠 Model Used

A simple Artificial Neural Network is used for classification.

```text
Input Image
     ↓
Flatten Layer
     ↓
Dense Hidden Layer
64 Neurons + ReLU
     ↓
Output Layer
10 Neurons + Softmax
     ↓
Predicted Product Category
```

### Model Components

* **Flatten:** Converts the image into a format suitable for the neural network.
* **Dense Layer:** Learns patterns from the image data.
* **ReLU:** Activation function used in the hidden layer.
* **Softmax:** Produces probabilities for the 10 product categories.

## 🔄 Project Workflow

```text
Load Fashion MNIST Dataset
        ↓
Explore Product Images
        ↓
Normalize Pixel Values
        ↓
Build Neural Network
        ↓
Compile Model
        ↓
Train Model
        ↓
Evaluate Accuracy
        ↓
Predict Product Category
        ↓
Compare Prediction with Actual Category
```

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Google Colab

## ⚙️ Model Training

The model is trained for **3 epochs** using:

* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy
* **Metric:** Accuracy
* **Validation Split:** 10%

The exact accuracy may vary slightly when the notebook is executed.

## 🔍 Prediction

After training, the model can classify images from the test dataset.

For example:

```text
Product Image
      ↓
Deep Learning Model
      ↓
Predicted Category
      ↓
Compare with Actual Category
```

The notebook also allows different test images to be selected by changing the `image_number` value.

## 💼 Business Application

The project demonstrates how an e-commerce company could use image classification to assist with product categorization.

### Traditional Process

```text
Product Image
      ↓
Employee Identifies Category
      ↓
Product Listed
```

### AI-Assisted Process

```text
Product Image
      ↓
Deep Learning Model
      ↓
Predicted Category
      ↓
Human Review
      ↓
Product Listed
```

### Possible Benefits

* Faster product listing
* Reduced repetitive manual work
* More consistent product categorization
* Improved product-search experience
* Ability to process large numbers of product images

## ⚠️ Limitations

The model may not classify every image correctly.

Some limitations include:

* Incorrect predictions
* Limited image resolution
* Similar-looking categories may be difficult to distinguish
* Fashion MNIST images are simpler than many real-world e-commerce images
* Human review may still be required

Therefore, businesses should consider model accuracy, data quality, risk, and human oversight before deploying an image-classification system.

## 👤 Human Role

AI predictions should be reviewed when necessary, especially for:

* Low-confidence predictions
* Unusual products
* Incorrect classifications
* Important product listings

The model can therefore **assist employees rather than completely replace human judgment**.

## 📁 Project Structure

```text
deep-learning-fashion-image-classification/
│
├── part-a/
│   └── deep-learning/
│       └── Deep_Learning_Fashion_Classification_Name.ipynb
│
├── screenshots/
│   └── fashion-image-prediction.png
│
└── README.md
```

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. The Fashion MNIST dataset will download automatically.
4. Explore the product images.
5. Train the neural network.
6. Check the test accuracy.
7. Try different image numbers for predictions.
8. Compare the predicted category with the actual category.

## 📚 Key Concepts

* Deep Learning
* Artificial Neural Networks
* Image Classification
* Fashion MNIST
* Input Layer
* Hidden Layer
* Output Layer
* ReLU
* Softmax
* Training
* Testing
* Accuracy
* Prediction

## 🎓 Key Learning

This practical demonstrates how Deep Learning can learn patterns from images and use those patterns to classify unseen products.

It also shows how AI-based image classification can support business processes such as **e-commerce product categorization and automated product listing**.

## 📸 Submission

The project includes:

* Completed Google Colab notebook
* Screenshot of a product image
* Predicted category
* Actual category

Suggested location:

```text
part-a/deep-learning/
```

## 👩‍💻 Project Information

**Project Type:** Academic / Educational Machine Learning Practical
**Domain:** Deep Learning & E-commerce
**Level:** Beginner
**Platform:** Google Colab
**Language:** Python
