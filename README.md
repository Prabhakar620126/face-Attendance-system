# 👨‍🏫 Face Recognition Attendance System

A smart attendance automation project using OpenCV, Face Recognition, and Python.<br>
This system detects faces in real time, recognizes registered students, and automatically marks attendance in a CSV file with Name, Time, and Date.<br>

## 📌 Project Overview<br>

The Face Recognition Attendance System is designed to automate the traditional attendance process.<br>
Instead of marking attendance manually, students just need to stand in front of the camera, and the system automatically:<br>

   -  Detects the face<br>
    
  - Compares it with the trained model<br>
    
  - Identifies the student<br>
    
   - Marks attendance in a CSV file<br>
    
  - Prevents duplicate entries<br>

This project was developed during the 4th semester to explore real-world applications of OpenCV, face embeddings, and computer vision.<br>

## ✨ Features<br>

✔ Real-time face detection<br>
✔ Face recognition using encodings<br>
✔ Automatic attendance marking<br>
✔ No duplicate entry for same day<br>
✔ stores attendance in .csv format<br>
✔ Easy to add new students<br>
✔ Clean and modular Python code<br>

| Technology                   | Purpose                     |
| ---------------------------- | --------------------------- |
| **Python**                   | Core programming            |
| **OpenCV**                   | Face detection              |
| **face_recognition Library** | Face encoding + recognition |
| **NumPy**                    | Data operations             |
| **CSV**                      | Attendance storage          |
| **OS / datetime**            | File & time handling        |

## 📸 How It Works<br>
1️⃣ Add Student Images<br>
  Place all student images inside the folder:<br>

2️⃣ Generate Encodings<br>
  This file scans all images and creates numeric encodings for the model.<br>

3️⃣ Run the Attendance System<br>
  The camera opens and recognizes faces in real time.<br>
  Attendance gets stored automatically in:<br>
## Sample Output:<br>
  Name,Time,Date<br>
    Prabhakar,10:25:32,2025-01-11<br>
    Rahul,10:27:15,2025-01-11<br>

##  📷 Documents  <br>
[Face Detection](https://github.com/Prabhakar620126/face-Attendance-system/blob/main/caputuring_image.png)<br>
[sample Video ](https://github.com/Prabhakar620126/face-Attendance-system/blob/main/sample%20video%20.mp4)<br>
[Project report ](https://github.com/Prabhakar620126/face-Attendance-system/blob/main/Mini%20Project%20Report.pdf)<br>
## 🚀 Future Improvements<br>

🔹 Add GUI using Tkinter / PyQt<br>
🔹 Add voice confirmation<br>
🔹 Deploy using Flask / Streamlit<br>
🔹 Store attendance in MySQL or Firebase<br>

## 👨‍💻 Author<br>

Prabhakar Kumar Shahi <br>
4th Semester – Information Technology<br>
GitHub: [LinkedIn Profile](https://github.com/Prabhakar620126)<br>
LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/prabhakar-kumar-shahi-b84851259/)<br>
