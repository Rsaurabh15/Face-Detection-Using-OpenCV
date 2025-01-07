#Face-Detection-Using-OpenCV

This project demonstrates how to perform face detection using Python and OpenCV. It utilizes OpenCV's pre-trained Haar Cascade Classifier to detect faces in both static images and real-time video streams from a webcam.

### Features:
- **Face Detection in Images**: Detect faces in a given image by applying Haar Cascade Classifier.
- **Real-time Face Detection**: Capture video from the webcam and detect faces in real-time.
- **Rectangle Bounding**: Once faces are detected, green rectangles are drawn around them.

### Technologies Used:
- Python
- OpenCV (opencv-python)

### Setup Instructions:
1. Install OpenCV using pip:
   ```bash
   pip install opencv-python
   ```
2. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/face-detection.git
   ```
3. Run the script for image face detection:
   ```bash
   python face_detection.py
   ```
4. Run the script for real-time webcam face detection:
   ```bash
   python webcam_face_detection.py
   ```

### How It Works:
- The project loads a pre-trained Haar Cascade Classifier (`haarcascade_frontalface_default.xml`) for detecting faces.
- It converts input images to grayscale to enhance detection accuracy.
- Detected faces are highlighted with green rectangles on the image or video frame.

### Contributions:
Feel free to fork this repository, create a pull request, and contribute to improving the project. You can enhance the accuracy or add new features like detecting multiple faces or integrating with other facial recognition systems.

---

This description provides an overview, installation instructions, and contribution guidelines to make your project easy to understand for anyone viewing it on GitHub.
