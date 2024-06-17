

<h1 align="center">Image Forgery Detection Using Convolutional Neural Networks</h1>

This repository contains two main folders:

1. **IFAKE_AI** - This folder contains the AI Jupyter notebook files used to create the proposed CNN model for forgery detection and classification. The notebook files demonstrate the process of training and testing the model on the FIDAC & CASIA dataset.

2. **IFAKE_WebApp** - This folder contains the web application project. The web application is built on the Django framework and provides a user-friendly interface for detecting image and video forgeries.

## Research Paper and Dataset

The [FIDAC dataset](https://ieee-dataport.org/documents/fidac-forged-images-detection-and-classification) is available on IEEE Dataport and contains original camera-clicked images along with their tampered versions. The dataset was used to train and test our proposed CNN model and compare it with other pre-defined models on various datasets combinations.




## Running the Web Application

To run the web application on Windows, Linux, or Mac, follow these steps:

1. Install Python3 and pip3
2. Clone this repository
3. Open a terminal and navigate to the IFAKE_WebApp folder
4. Run the following command to install the required Python packages:

    ```
    pip3 install -r requirements.txt
    ```

5. Run the following command to start the web application:

    ```
    python manage.py runserver
    ```

6. Open a web browser and go to http://127.0.0.1:8000/ to access the web application.

## Screenshots
![image](https://github.com/jahnavi-213/Digital-Image-Forgery-Detection-Using-Convolutional-Neural-Networks/assets/123347285/6b4a7f63-e3df-4bd5-a52b-2100069ee85a)
<br />
![image](https://github.com/jahnavi-213/Digital-Image-Forgery-Detection-Using-Convolutional-Neural-Networks/assets/123347285/eb9ce7bf-87c1-449d-8e89-47272be5c161)
<br />
![image](https://github.com/jahnavi-213/Digital-Image-Forgery-Detection-Using-Convolutional-Neural-Networks/assets/123347285/6610ce1d-7b97-4902-a460-a6e850f25f0c)





The screenshots show different features of our web application, including the image forgery detection functionality, and the ability to upload and view results of detected forgeries.


