# Face-Recognition

PROBLEM STATEMENT:
- Face recognition with OpenCV, Python, and deep learning
- To perform face recognition in any way - images or video streams using OpenCV, Python, and deep learning.
- Recognize faces in a single image (based on encodings from your dataset).
- Recognize faces in a live video stream from your webcam and output a video or recognize faces in a video file residing on disk and output the processed video to disk.
- Encoding of the faces is done using OpenCV and deep learning. Before you can encode faces in images you first need to detect them (face detection is implicit), you can use any appropriate method of your choice. 

CODE DETAILS:
- Major Libraries used are face_recognition and cv2.
- More on face_recognition : https://face-recognition.readthedocs.io/en/latest/_modules/face_recognition/api.html#face_encodings
- The histogram of oriented gradients (HOG) model has been used, However cnn model can be used. 
- "hog" is less accurate but faster on CPUs. "cnn" is a more accurate deep-learning model which is GPU/CUDA accelerated 
