Real-Time Facial Expression Recognition
This project utilizes deep learning and computer vision techniques to perform real-time facial expression recognition. It detects facial expressions from live video using a webcam and predicts the corresponding emotion in real-time.


Features
Real-time facial expression detection and emotion classification
Supports seven emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral
Uses Convolutional Neural Networks (CNNs) for facial expression recognition
Provides a graphical user interface (GUI) for a user-friendly experience
Requirements


To run the project, make sure you have the following dependencies installed:
Python 3.x, TensorFlow, OpenCV (cv2), Matplotlib, Numpy, and Keras


Usage
Clone or download the repository from GitHub.
Install the required dependencies by running the following command:

"pip install -r 'upper requirements'"


Prepare the training and testing data:
Create two separate directories: training and test. 
[Already DONE with the FER 2013 Dataset, you just have to download it from this link: https://www.kaggle.com/datasets/msambare/fer2013] Organize your facial expression images into subdirectories inside training and test, with each subdirectory representing a specific emotion class. The images should be in grayscale and resized to 48x48 pixels.
Ensure the image filenames in each subdirectory are unique.


Train the model:
Open the Jupyter Notebook or Python script file that contains the model creation and training code.
Modify the file paths in the load_data() function to match the directories you created in step 3.
Run the script to train the model using the provided training data. The trained model will be saved for later use.
Run the real-time facial expression recognition:


Open the Jupyter Notebook or Python script file that contains the capture_emotion() function.
Load the trained model by modifying the model variable to point to the saved model file.
Run the script to start the real-time facial expression recognition.
A new window will open displaying the live video stream from your webcam. The predicted emotion will be overlaid on detected faces in real-time.
Contributions
Contributions to this project are welcome! If you have any ideas, improvements, or bug fixes, feel free to open an issue or submit a pull request on GitHub.
