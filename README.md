# Human-Movement-Tracking-with-Mediapipe-and-OpenCV
Human Movement Tracking in Real Time
Human Movement Tracking with Mediapipe and OpenCV

Required Libraries:

1. openCV - a powerful tool for image processing and image recognition projects.

2. mediapipe - a strong python framework for building multimodal (eg. video, audio, any time series data), cross platform (i.e Android, iOS, web, edge devices) applied ML pipelines.

Features:

1. This project works with the webcam, it detects and track the facial, body and hand gestures in real time

2. After detecting and identifying the attiributes it is open for any ML projects to apply, such as- Emotion Recognition, Activity Recognition etc. As I was instructed to complete an assignment that can track the CSO's(Customer Service Officer)
movements, I kept it open for any ML solutions that can be implemented later using this model.

3. It also has a 15 sec pulse feature. That means, after every 15 seconds, the program will automatically append all the
'landmarks' i.e the coordinates of the facial, pose, hands- of the previous 15 seconds to a list in a form of a dictionary. In that way, it can be used later as a dataset to study the behavior of the CSO.
