# Mask Detection using Deep Learning
This project is a deep learning application that predicts if a person is wearing a mask or not based on an input image. The model was trained using a dataset from Kaggle, and the application is deployed using **Streamlit**.

## Project Structure 
* **requirements.txt**: Lists all libraries used in this project. 
* **mask_detection_model.tflite**: Trained model saved in TensorFlow Lite format for efficient inference. 
* **face_Mask_Detection_using_CNN.ipynb**: Jupyter Notebook with code for training and evaluating the model.
* **streamlit_app.py**: Streamlit application for running the mask detection model interactively.

## Usage 
1. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
   
  2.Run the Streamlit app: 
```
streamlit run streamlit_app.py
```

## Model
The model is a Convolutional Neural Network (CNN) trained to detect face masks, optimized and converted to TensorFlow Lite format.

## Demo App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://facemask-project.streamlit.app/)
