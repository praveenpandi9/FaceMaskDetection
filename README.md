# Face Mask Detection Using YOLOv5

## Introduction
This project utilizes YOLOv5 to detect the presence of face masks in images. The model is trained to identify three classes: 'with_mask', 'without_mask', and 'mask_weared_incorrect'. The training dataset is obtained from Kaggle, containing images with corresponding annotations.

## Project Structure
- **project.ipynb**: This Jupyter Notebook contains the source code for training and testing the YOLOv5 model.
- **yolov5**: This directory holds the customized YOLOv5 model.
- **datasets**: Contains the dataset, including the archive.zip file downloaded from Kaggle.

## Steps to Run the Code
1. Install the required dependencies by executing `pip install -r requirements.txt`.
2. Download the dataset from Kaggle: [Face Mask Detection Dataset](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection).
3. Place the downloaded archive.zip file in the datasets directory.
4. Run the project.ipynb notebook to train and test the model.

## Code Flow
1. Preprocessing of the dataset.
2. Splitting the dataset into training and testing sets.
3. Conversion of annotations from XML format to TXT format.
4. Training the YOLOv5 model using the annotated data.
5. Testing the trained model on custom images.
6. Generation of necessary plots and graphs for evaluation.
7. The trained model's weights are saved in the directory models/mask_yolov5.pt.

This project demonstrates the application of YOLOv5 in face mask detection, contributing to public health and safety measures.
