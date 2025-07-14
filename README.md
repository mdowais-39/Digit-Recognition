# **Digit Recognition with Object Detection 🚀**

### **Visualize digits with precise bounding boxes using TensorFlow and MNIST!**

## 

## **🌟 Project Overview**

Welcome to the Digit Recognition with Object Detection project! This exciting project combines classification and localization to not only identify digits (0-9) but also pinpoint their locations in images using bounding boxes. Built with TensorFlow and the MNIST dataset, it showcases deep learning in action with stunning visualizations of predicted and true bounding boxes, complete with Intersection over Union (IoU) metrics to evaluate performance. 🎉





## **🎯 Features**



🔍 Digit Classification: Accurately identifies digits (0-9) using a convolutional neural network.

📍 Bounding Box Localization: Predicts precise coordinates for digit locations in images.

🖼️ Visualizations: Displays digits with red (predicted) and green (true) bounding boxes, highlighting classification accuracy and IoU scores.

⚙️ Data Preprocessing: Loads and preprocesses the MNIST dataset with TensorFlow Datasets, padding images to 75x75 and normalizing coordinates.

📊 Metrics: Evaluates model performance with classification accuracy and IoU for localization.





## **🛠️ Installation**

**Get started in just a few steps! 🚀**

**Prerequisites**



Python 3.11 or later 🐍

A passion for machine learning! 😄



**Steps**



Clone the Repository:

git clone (https://github.com/mdowais-39/Digit-Recognition)

cd digit-recognition-object-detection





Set Up a Virtual Environment (recommended)

**Install Dependencies**:

pip install -r requirements.txt





**Dataset Download:**

The MNIST dataset is automatically downloaded via TensorFlow Datasets when you run the notebook.





## 

## **🚀 Usage**

Dive into the project with these simple steps:



Launch the Jupyter Notebook:

jupyter notebook Object\_Detection.ipynb





**Explore the Notebook:**



📚 Section 1: Imports libraries like TensorFlow, NumPy, Matplotlib, and PIL.

🖌️ Section 2: Defines visualization utilities for drawing bounding boxes and displaying digits.

🗂️ Section 3: Loads and preprocesses the MNIST dataset, padding images and generating normalized bounding box coordinates.

📈 Visualization: Shows predicted vs. true labels with bounding boxes and IoU metrics.





## **Model Training:**



The notebook uses a pre-trained model (model.predict). To train your own, add model definition and training code (see Future Improvements).

Run the notebook to see predictions and visualizations.





## **Output:**



📷 Visualizations of digits with red (predicted) and green (true) bounding boxes.

🔴 Incorrect predictions are highlighted in red.







📊 IoU scores indicate localization accuracy (red if below 0.6).









## **🗃️ Dataset**

The project uses the MNIST dataset via TensorFlow Datasets. Images are padded to 75x75 pixels, and bounding box coordinates are normalized for localization tasks.



## **📸 Visualizations**

The display\_digits\_with\_boxes function creates stunning visuals:



Digits: Displayed with predicted (red) and true (green) bounding boxes.

Labels: Predicted labels turn red if incorrect.

IoU Scores: Localization accuracy is shown, with low scores (<0.6) in red.







## **🔮 Future Improvements**



🛠️ Add model definition and training code for a self-contained notebook.

🔄 Implement data augmentation for improved robustness.

🔬 Experiment with advanced architectures like Yoconvolutional neural networks for better localization.

📷 Support multiple digits per image for real-world applications.





## **🤝 Contributing**

💡 Follow these steps to contribute:



Fork the repository 🍴

Create a feature branch (git checkout -b feature-branch)

Commit your changes (git commit -m "Add cool feature")

Push to the branch (git push origin feature-branch)

Open a pull request 🚀





## **🙌 Acknowledgments**



TensorFlow for the awesome deep learning framework.

MNIST Dataset for the classic digit dataset.

TensorFlow Datasets for seamless data loading.





Star this repo if you found it helpful! 🌟 Let's make digit recognition even better together!

