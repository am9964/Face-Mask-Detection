# Face Mask Detection
An application of Convolution Neural Networks to classify if a person is wearing a face mask or not (binary classification). 

## Dataset
The dataset used has 2 classes each with images of people with and without a mask. The data has been divided into Train, Validation and Test Set and is loaded using ImageDataGenerator.

The dataset maybe accessed <a href = "https://drive.google.com/drive/folders/1MaU49YgSFBqGbMVImh6k6f__q-_mowck?usp=sharing">here</a>.

## Model Architecture
<img src = "assets/model.png" height = 600px width = 400px>

The model in .h5 format may be downloaded from <a href = "https://drive.google.com/file/d/161FyMUewCUbKtiBaMTc87oGY7qtPRMYp/view?usp=sharing">here</a>.

## Usage
Please download the trained <a href = "https://drive.google.com/drive/folders/1MaU49YgSFBqGbMVImh6k6f__q-_mowck?usp=sharing">model</a> and move it to a directory names *models*. Please ensure that the path to model is *"models/model.h5"*.

- Cloning the Repository: 

        git clone https://github.com/am9964/Face_Mask_Detection
        
- Entering the directory: 

        cd Face_Mask_Detection
        
- Setting up the Python Environment with dependencies:

        pip install -r requirements.txt
        
- Entering the test directory: 

        cd test

- Running the file:

        python3 test.py
