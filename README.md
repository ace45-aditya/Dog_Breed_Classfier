# Dog Breed Identification using Deep Learning

## Overview

This project classifies the breed of a dog from an input image using **Transfer Learning** with TensorFlow. A pre-trained deep learning model is fine-tuned on the Dog Breed Identification dataset to accurately recognize different dog breeds.

## Features

- Dog breed classification from images
- Transfer Learning using TensorFlow Hub
- Image preprocessing and data augmentation
- Model training and evaluation
- Prediction on unseen dog images

## Technologies Used

- Python
- TensorFlow
- TensorFlow Hub
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset

This project uses the **Dog Breed Identification** dataset available on Kaggle.

The dataset is **not included** in this repository because of its large size.

Download the dataset and place it inside a folder named:

```text
data/
```

The directory structure should be:

```text
data/
├── train/
├── test/
└── labels.csv
```

## How to Run

1. Clone this repository.
2. Download the Dog Breed Identification dataset from Kaggle.
3. Place the dataset inside the `data/` directory.
4. Install the required dependencies:

```bash
pip install -r requirements.txt
```

5. Open `Dog_Breed_Classifier.ipynb`.
6. Run the notebook sequentially from start to finish.

## Model

The project uses **Transfer Learning** with a pre-trained image classification model from TensorFlow Hub, enabling efficient training and high classification accuracy.

## Repository Structure

```text
Dog-Breed-Classifier/
│
├── Dog_Breed_Classifier.ipynb
├── README.md
├── requirements.txt
└── data/
```

> **Note:** The `data/` folder is not included in this repository. Download the dataset separately from Kaggle before running the notebook.

## Author

**Aditya Prasad Phadatare**
