# 👨‍🏫 Face Recognition Attendance System

A smart attendance automation project using OpenCV, Face Recognition, and Python.
This system detects faces in real time, recognizes registered students, and automatically marks attendance in a CSV file with Name, Time, and Date.

## 📌 Project Overview

The Face Recognition Attendance System is designed to automate the traditional attendance process.
Instead of marking attendance manually, students just need to stand in front of the camera, and the system automatically:

  Detects the face
  
  Compares it with the trained model
  
  Identifies the student
  
  Marks attendance in a CSV file
  
  Prevents duplicate entries

This project was developed during the 4th semester to explore real-world applications of OpenCV, face embeddings, and computer vision.

## ✨ Features

✔ Real-time face detection
✔ Face recognition using encodings
✔ Automatic attendance marking
✔ No duplicate entry for same day
✔ stores attendance in .csv format
✔ Easy to add new students
✔ Clean and modular Python code

| Technology                   | Purpose                     |
| ---------------------------- | --------------------------- |
| **Python**                   | Core programming            |
| **OpenCV**                   | Face detection              |
| **face_recognition Library** | Face encoding + recognition |
| **NumPy**                    | Data operations             |
| **CSV**                      | Attendance storage          |
| **OS / datetime**            | File & time handling        |

📸 How It Works
1️⃣ Add Student Images

  Place all student images inside the folder:

2️⃣ Generate Encodings
  This file scans all images and creates numeric encodings for the model.

3️⃣ Run the Attendance System
  The camera opens and recognizes faces in real time.
  Attendance gets stored automatically in:
## Sample Output:
  Name,Time,Date
Prabhakar,10:25:32,2025-01-11
Rahul,10:27:15,2025-01-11

##📷 Screenshots 
![Face Detection](<img width="1229" height="786" alt="image" src="https://github.com/user-attachments/assets/f0553f4e-fce5-4c80-8b3a-73c3d6025a03" />
)
![Attendance CSV](images/attendance.png)
![sample Video ](https://github.com/Prabhakar620126/face-Attendance-system/blob/main/sample%20video%20.mp4)

## 🚀 Future Improvements

🔹 Add GUI using Tkinter / PyQt
🔹 Add voice confirmation
🔹 Deploy using Flask / Streamlit
🔹 Store attendance in MySQL or Firebase

## 👨‍💻 Author

Prabhakar Kumar Shahi 
4th Semester – Information Technology
GitHub: [LinkedIn Profile](https://github.com/Prabhakar620126)
LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/prabhakar-kumar-shahi-b84851259/)
