# Filter-and-Song-suggestion-bot
In this project, we recognize real images of emotions (Angry, Digusted, Fearful, Happy, Neutral, Sad, Surprised) in order to classify an incoming image as one of seven emotions. After identifying the emotion, the bot then recommends a song that would be suitable for the given emotion. 

## Part 1: Identifying emotions
Emotion identification is done through a pre trained model developed in Keras with Tensorflow.
Real time face detection is done using OpenCV.

## Part 2: Recommending songs
Stored songs according to different emotions 'angry', 'disgusted', 'fearful', 'happy', 'neutral', 'sad', 'surprised'. 
Recommend a random song from the list of songs under the emotion given as input.

