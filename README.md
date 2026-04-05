# Frontal_Face_Recognition_using_CV2
**Description:-**
This project is a simple real-time face detection system built using OpenCV in Python. It uses a pre-trained Haar Cascade classifier to detect human faces through a webcam and draws bounding boxes around detected faces.
This is a beginner-friendly project to understand computer vision basics and how face detection works.

**🚀 Features**

Real-time face detection using webcam
Uses Haar Cascade classifier
Draws rectangle around detected faces
Lightweight and easy to run
Beginner-friendly implementation

**🛠️ Technologies Used**

Python 
OpenCV (cv2)
Haar Cascade Classifier

**📂 Project Structure**

Face-Recognition-OpenCV/
│── README.md
│── face_detection.py

**⚙️ Installation & Setup**

**Step 1**: Clone the Repository
git clone https://github.com/your-username/face-recognition-opencv.git
cd face-recognition-opencv
**Step 2**: Install Dependencies
pip install opencv-python
**Step 3**: Run the Project
python face_detection.py

**💻 Code Explanation**

cv2.VideoCapture(0) → Access webcam
CascadeClassifier() → Load Haar Cascade model
detectMultiScale() → Detect faces
cv2.rectangle() → Draw box around face
Press 'a' key to exit the window

**🧠 How It Works**

Webcam captures live video
Frame is converted to grayscale
Haar Cascade detects faces
Rectangles are drawn around detected faces
Output displayed in real-time

**📸 Output**

Opens webcam feed
Detects face(s)
Shows bounding boxes

**⚠️ Note**

Ensure your webcam is working
Good lighting improves detection accuracy

**📈 Future Improvements**

Face recognition (identify person)
Add deep learning models (like CNN)
Save detected faces
Integrate with attendance system

**🙌 Author**
_ARYAN SONI_
