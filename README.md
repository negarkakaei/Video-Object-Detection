This project implements real-time object detection in video streams using the YOLO (You Only Look Once) deep learning model and OpenCV. The system processes each video frame to detect and classify objects, drawing bounding boxes around detected objects and annotating them with confidence scores. Key features include:

- **Preprocessing:** Frames are resized to 416x416 pixels and normalized for input into the YOLO network.
- **Detection:** The YOLO model identifies objects and provides bounding box coordinates, confidence scores, and class probabilities.
- **Non-Maximum Suppression (NMS):** Overlapping bounding boxes are filtered to retain the most accurate detections.
- **Annotation:** Detected objects are marked with colored bounding boxes and labeled with class names and confidence scores.
