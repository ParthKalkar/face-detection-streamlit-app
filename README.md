# face-detection-streamlit-app
Welcome to the face-detection-streamlit-app repository! This project provides a simple web application for detecting faces in images using the HAAR cascade frontal face algorithm. The web app is built using Streamlit, a powerful Python library for creating interactive data science applications.

The app is designed to be easy to use, even for those with no experience in computer vision or data science. With just a few clicks, you can start with a video and quickly see where faces are detected. The app also includes a range of customization options, allowing you to adjust parameters such as the scale factor and minimum size of detected faces.

We hope you find this app useful and informative. Feel free to contribute to the project, provide feedback, or suggest new features. Happy face detecting!

## Face Detection
Face Detection is an artificial intelligence(AI) based computer technology used to find and identify human faces in digital images or video settings. Face detection technology can be applied to various fields including security, biometrics, law enforcement, etc. 

## HAAR Cascade
The HAAR cascade algorithm is a popular method for detecting faces in images, using a set of pre-trained classifiers to identify the locations of faces. In this app, we provide a user-friendly interface for uploading images and visualizing the results of face detection

## Technologies
1. Streamlit 
2. HAAR Cascade
3. Python
4. OpenCV

## Run
To run the face-detection-streamlit-app, follow these steps:

1. Clone the repository onto your local machine by running the command `git clone <repository_url>` in your terminal/command prompt. 

2. Navigate to the directory of the repository using the `cd` command. 

3. Create a virtual environment for the app and activate it using the following commands:
   
   On Windows: 
   ```
   python -m venv venv
   venv\Scripts\activate
   ```
   
   On Linux/Mac:
   ```
   python3 -m venv venv
   source venv/bin/activate
   ```

4. Install the necessary dependencies using the following command:
   
   ```
   pip install -r requirements.txt
   ```

5. Run the app by executing the following command:

   ```
   streamlit run app.py
   ```
   
6. The app will now be running locally on your machine. You can access it by opening your web browser and navigating to `http://localhost:8501`. 

7. To use the app, simply click on the `detect faces` and the app will detect the faces and highlight them in the image. 


