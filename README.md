# Attendance System using One Hand and Face

This project is an AI-powered smart attendance system that identifies students using **facial recognition** and **hand gesture detection (single hand)**. The goal is to automate the traditional attendance process using computer vision techniques for faster and more reliable results.

## 🚀 Features

- 👤 **Face Recognition**: Uses webcam to detect and match student faces.
- ✋ **Single-Hand Detection**: Recognizes specific hand gestures to confirm presence.
- 🕵️ Real-time processing using **OpenCV** and **CVZone**
- 🗂️ Easy to update attendance records.
- 💡 Ideal for classrooms, labs, or meetings where minimal manual interaction is preferred.

## 🛠️ Technologies Used

- Python
- OpenCV
- CVZone
- MediaPipe
- NumPy
- Face Recognition Library
- Streamlit (if UI is integrated)

## 📁 How It Works

1. The system captures video feed using the webcam.
2. Detects the face of the user and matches it with stored images.
3. Simultaneously checks if a hand is raised and the correct gesture is made.
4. On successful match of face + hand gesture → attendance is marked.

## 🔧 Setup Instructions

```bash
git clone https://github.com/Dksharma1102/attendance_system_using-one-hand-and-face.git
cd attendance_system_using-one-hand-and-face
pip install -r requirements.txt
python main.py

📸 Demo
![Screenshot 2025-06-07 084243](https://github.com/user-attachments/assets/23080816-feae-496a-8a71-a4574948ba91)
![image](https://github.com/user-attachments/assets/7a51fc08-37bb-411a-a812-3259a173efac)
![image](https://github.com/user-attachments/assets/f091f0a4-92dd-4168-99b8-d8af33782954)




📄 License
This project is open-source and free to use for academic or non-commercial purposes.
