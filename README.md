# Glaucoma-Detection-using-CNN [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://glaucoma-detector.streamlit.app)

Link: https://glaucoma-detector.streamlit.app

A deep learning-based glaucoma detection method is being developed in this project. Convolutional neural networks (CNNs), which are trained using publically accessible datasets of fundus images of healthy and glaucomatous eyes, are used in this system to classify images.

## Details
* Step 1:-In this project, we have collected three publicly available datasets namely ACRIMA,DRISTHI-GS amd RIM-ONE.
* Step 2:-We have combined the three datasets to form a Combined dataset.
* Step 3:-Data Augumentation is applied to Combined dataset in order to increase training data and boost the model's performance.
* Step 4:-The combined dataset is split into training, testing, and validation data.
* Step 5:-A Keras CNN model was built and trained using training data.
* Step 6:-The model was evaluated using test data and metrics including accuracy (98%) and precision , recall , and F1-score . For future use, we saved the model file in h5 format.
* Step 7:-Then we built a simple streamlit app for hosting on web.

## Requirements
To run this project, you need to have the following software installed:
* Python 3.8
* Tensorflow 2.12.0
* keras 2.12.0
* plotly-express 0.4.1
* numpy 1.22.4
* pandas 1.5.3
* streamlit 1.21.0
* streamlit_ext 0.1.7

You can install these packages using pip, by running the following command:
pip install tensorflow keras streamlit 

## Usage
To use our project - go to this link https://glaucoma-detector.streamlit.app

* The web app opens up in a new tab. Then you can use it for classifying. That's it!

* Upload a (jpg,png,jpeg) fundus image/images of eye. Our model predicts whether affected by glaucoma or not.

## License
[MIT LICENSE](https://github.com/SaiHitesh16/Glaucoma-Detection-using-CNN/blob/main/LICENSE)
