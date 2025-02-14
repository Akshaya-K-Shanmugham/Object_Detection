# Object_Detection

Object Detection and Face Recognition System
A comprehensive computer vision system that combines YOLOv8-based object detection with face recognition capabilities. The system can process real-time webcam feeds, video files, YouTube videos, and static images.

🌟 Features
=>Object Detection:
1)Real-time object detection using YOLOv8
2)Support for multiple input sources:
                                  *Webcam feed
                                  *Local video files
                                  *Static images
3)Adjustable confidence and IOU thresholds
4)Visual bounding box display with class labels

=>Face Recognition
1)Real-time face detection and recognition
2)Support for multiple known faces
3)Display of recognized names with bounding boxes
4)Unknown face handling
5)Face distance comparison for better accuracy

🛠️ Requirements:
Python 3.x
OpenCV (cv2)
YOLOv8 ONNX model
face_recognition
numpy
imread_from_url (for image URL processing)
