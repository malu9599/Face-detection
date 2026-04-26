📷 Real-Time Face Detection using OpenCV

This project demonstrates real-time face detection using your laptop’s webcam with the help of the OpenCV library in Python.

It captures live video, detects faces in each frame, and draws bounding boxes around them.

🚀 Features
Real-time face detection via webcam
Uses Haar Cascade Classifier
Lightweight and fast
Easy to set up and run
🛠️ Requirements
Python 3.x
OpenCV

Install dependencies using:

pip install opencv-python
▶️ How to Run
Clone this repository:
git clone https://github.com/your-username/face-detection.git
cd face-detection
Run the script:
python face_detection.py
A window will open showing your webcam feed with detected faces.
Press q to exit.
🧠 How It Works
The script uses a pre-trained Haar Cascade model:
haarcascade_frontalface_default.xml
Frames from the webcam are:
Captured in real time
Converted to grayscale
Passed through the face detection model
Detected faces are highlighted with rectangles
📁 Project Structure
face-detection/
│── face_detection.py
│── README.md
🔧 Customization

You can tweak detection performance by adjusting:

scaleFactor=1.3
minNeighbors=5
minSize=(30, 30)
scaleFactor → Image scaling
minNeighbors → Detection accuracy
minSize → Minimum face size
💡 Future Improvements
Add eye detection
Implement face recognition
Save detected faces as images
Use deep learning models (DNN / MediaPipe)
📜 License

This project is open-source and available under the MIT License.

🙌 Acknowledgements
OpenCV for providing powerful computer vision tools
