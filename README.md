# Hand Gesture Recognition using CVZone

https://user-images.githubusercontent.com/88562515/236702632-293c8314-7898-4b80-8fa8-2310b63bbb1f.mp4

This code uses the CVZone library to detect hand gestures and recognize them using a pre-trained neural network model. The hand detection is performed using the Mediapipe library, which provides a fast and accurate way to track hand landmarks in real-time video.

The code captures video from a camera (in this case, a mobile device camera) using an IP address, processes it to detect the hand and extract a cropped image of the hand gesture. The cropped image is then resized to a fixed size and fed into a pre-trained neural network model to classify the gesture. The predicted class label is then displayed on the video feed along with a bounding box around the hand.

The code uses the following libraries:

# OpenCV (cv2) #
## CVZone #
## Mediapipe # 
## NumPy #
## Math #
To use this code, make sure you have the required libraries installed and the pre-trained neural network model and labels files available in the specified folders.

This code can be extended to recognize and classify other types of hand gestures, as well as to perform other tasks such as gesture-based control of a device or application.
