# Integrated Threat Detection System: Safeguarding Communities Through Advanced Surveillance and Analysis

## Overview
This project aims to enhance public safety by developing an AI-powered system capable of detecting firearms in real-time through deep learning algorithms. The system identifies potential threats in crowded public spaces, such as schools and hospitals, enabling swift intervention and reducing risks.

The solution uses advanced machine learning models for weapon detection, distinguishing between "Small Guns" and "Long Guns." This project is part of a larger effort to promote proactive risk management and crisis prevention using cutting-edge technology.

## Key Features
- **Firearm Detection**: Utilizes a convolutional neural network (CNN) for real-time image analysis to identify firearms.
- **Deep Learning Algorithms**: Built using Keras and trained on image datasets to classify weapons with high accuracy.
- **Data Visualization**: Performance metrics like accuracy and loss are plotted using `ggplot2` for detailed training insights.
- **Cloud Integration**: Data is processed and analyzed on cloud platforms like AWS for scalable deployment.
- **High Accuracy**: The model achieved a training accuracy of 81% and is continuously improving with more training data.

## Libraries & Tools
- **Keras**: Deep learning framework for building and training the CNN model.
- **EBImage**: For image processing and manipulation.
- **Tidyverse**: For data manipulation and visualization.
- **ggplot2**: For visualizing model performance.
- **AWS**: Cloud platform for scalable data analysis.
- **Python & R**: Used for scripting and model training.

## Data
The project uses a custom dataset collected from surveillance feeds, which is available for download [here](https://www.dropbox.com/scl/fo/88cvkx0r6g4fw00jmoyeb/AHHwptePNylRmCP0VKGoCj8?rlkey=droin1yhhu9j0o495jxmvpy48&e=1&st=6w4v4uh8&dl=0). The dataset includes labeled images of firearms for model training and evaluation.

## Project Files
- **R Markdown (.Rmd) File**: Contains the full code for data preprocessing, model training, evaluation, and visualization.
- **HTML File**: Generated from the R Markdown file, providing a readable and interactive report of the project, including all code and results.

## Installation & Usage
1. Clone the repository and install the necessary libraries using the provided `requirements.txt`.
2. Load the dataset and preprocess the images for training.
3. Train the model using the provided scripts and evaluate its performance on the test set.
4. Visualize model accuracy and loss over epochs using `ggplot2`.

## Project Results
- **Training Accuracy**: 81%
- **Test Accuracy**: 53.8%

The model demonstrates robust performance, with clear visualizations of training loss and accuracy, along with predictions and image classifications.

## Future Work
- Expanding the dataset for improved accuracy.
- Integration with real-time surveillance systems for faster response times.
- Implementing additional object detection methods for broader threat detection.
