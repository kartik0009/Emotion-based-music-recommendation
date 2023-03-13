#Emotion-Based Music Recommendation Project
This is a project that uses machine learning to recommend music based on the emotions of the user. The application is built using Flask, Tensorflow, and NumPy. The system asks the user to select the language of the songs and then asks to select the particular. The system then captures current emotion of the user, and the system provides the required youtube link.

#Installation
To use this application, you must first install Flask, Tensorflow, and NumPy. You can do this by running the following command:

Copy code
pip install flask tensorflow numpy cv2 keras.models webbrowser
Usage
To start the application, navigate to the root directory and run the following command:

Copy code
python app.py
Once the application is running, you can access it by navigating to http://localhost:5000 in your web browser.

On the homepage, you will see a form where you can the language of the songs you want to listen to and then asks to select a particular singer. Once you submit the form, the system will provide the required youtube link.

#Dataset
The dataset used in this project is the [Haar Cascades for Face Detection]([https://pages.github.com/](https://www.kaggle.com/datasets/gpreda/haar-cascades-for-face-detection)) dataset.

#Machine Learning Model
The machine learning model used in this project is a neural network that was trained on the EmoReact dataset. The model takes in the audio data from a song and predicts the emotion that it is most suitable for.

#Credits
This project was created by Me(Kartik Talwar) and Iresh Kumar Singla. 
