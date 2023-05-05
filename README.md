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

1. Clone the repository onto your local machine by running the command `git clone https://github.com/ParthKalkar/face-detection-streamlit-app` in your terminal/command prompt. 

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

7. To use the app, simply click on the `detect faces` button and the app will detect the faces and highlight them in the image. 

## Output


https://user-images.githubusercontent.com/50231750/236465178-f9874c92-5c9f-41f8-a86e-a0b7e38b4384.mp4



## References
Here are references for the HAAR cascade algorithm and Streamlit:

HAAR cascade algorithm:
* Viola, P., & Jones, M. (2001). Rapid object detection using a boosted cascade of simple features. Proceedings of the 2001 IEEE Computer Society Conference on Computer Vision and Pattern Recognition. CVPR 2001.

* Bradski, G. (1998). Computer Vision Face Tracking for Use in a Perceptual User Interface. Intel Corporation.

* OpenCV documentation: https://docs.opencv.org/2.4/modules/objdetect/doc/cascade_classification.html

Streamlit:
* Streamlit documentation: https://docs.streamlit.io/en/stable/
* “Streamlit: The Fastest Way to Build Custom ML Tools” (blog post): https://towardsdatascience.com/streamlit-the-fastest-way-to-build-custom-ml-tools-f6f15bd5006a
* “How to Build an App with Streamlit” (video tutorial): https://www.youtube.com/watch?v=_9WiB2PDO7k&t=138s

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
