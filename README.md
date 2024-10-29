# Pneumonia Detection System 
This Pneumonia Detection System is a deep learning-based web application designed to assist in the detection of pneumonia from chest X-ray images. Built using Convolutional Neural Networks (CNNs) for image classification and a Flask app for a simple user interface, this system provides users with an accessible and intuitive diagnostic tool.

# Features 

  • Pneumonia Detection: Uses a pre-trained CNN model to analyze and classify chest X-ray images as "Normal" or "Pneumonia".
  
  • User-Friendly Interface: Flask web application provides a straightforward interface for uploading and viewing results.
  
  • Real-time Results: Get instant predictions after uploading the X-ray image.
  
  • Accurate and Reliable: Built on robust deep learning models to ensure high accuracy in prediction.
  
# Tech Stack 
• Frontend: HTML/CSS for simple, responsive UI elements.

• Backend: Flask for routing and handling user input.

• Machine Learning Model: Convolutional Neural Network (CNN) trained on chest X-ray datasets.

# Getting Started
Clone the Repository:

    git clone https://github.com/your-username/pneumonia-detection-system.git
Navigate to the Project Directory:

    cd pneumonia-detection-system
Install Dependencies:

    pip install -r requirements.txt
Run the Application:

    python app.py
    
Access the Web Interface: Open your browser and go to http://127.0.0.1:5000 to access the app.

# How It Works 
• Upload an X-ray Image: Users upload a chest X-ray image to be analyzed.

• Model Prediction: The CNN model processes the image and classifies it as "Normal" or "Pneumonia".

• Display Results: The prediction result is displayed on the UI.
# Dataset 
The CNN model is trained on a publicly available chest X-ray dataset, ensuring reliable results.

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

# License
This project is open source and available under the MIT License.
