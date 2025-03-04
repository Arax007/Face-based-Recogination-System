# 🚀 Face Recognition Based Attendance System

## 🎯 Overview
This project is an **AI-powered Face Recognition Based Attendance System** that automates attendance tracking using real-time face detection and recognition. It features an intuitive **Tkinter-based GUI** for seamless user interaction and employs **OpenCV** for accurate face detection. Attendance data is securely stored in **CSV files**, ensuring easy management and access.

---

## 🔥 Features
✔️ **AI-Powered Face Recognition** – Uses Haarcascade for real-time face detection.  
✔️ **Effortless User Registration** – Capture and store student images securely.  
✔️ **Automated Attendance Marking** – Recognizes faces and logs attendance with timestamps.  
✔️ **Interactive GUI** – User-friendly interface built with Tkinter.  
✔️ **Secure Access** – Password protection for new user registration.  
✔️ **Live Attendance Tracking** – Displays daily attendance in tabular format.  
✔️ **Data Storage** – Attendance records are automatically saved in CSV format.

---

## 🛠️ Technologies Used
- **Programming Languages**: Python, OpenCV, Tkinter  
- **Data Processing**: NumPy, Pandas, CSV  
- **Machine Learning**: LBPH Face Recognizer (`cv2.face_LBPHFaceRecognizer_create()`)  
- **UI/UX**: Tkinter-based graphical user interface  

---

## 📥 Installation
### Prerequisites
Ensure you have **Python 3.7+** installed and run the following command to install the dependencies:

```sh
pip install opencv-python numpy pandas pillow
```

---

## 📂 Project Structure
```
FaceRecognitionAttendance/
│-- haarcascade_frontalface_default.xml  # Pre-trained Haarcascade model for face detection
│-- main.py                              # Main Python script for GUI and face recognition
│-- LICENSE                              # License file
│-- StudentDetails/                      # Stores student details
│-- TrainingImage/                       # Stores images of registered users
│-- TrainingImageLabel/                  # Stores trained models
│-- Attendance/                          # CSV records of attendance
```

---

## 🚀 How to Use
1️⃣ **Run the Application**
```sh
python main.py
```

2️⃣ **Register a Student**  
- Enter **Student ID** and **Name**.  
- Click **Take Images** to capture face data.  
- Click **Save Profile** to store the trained model.

3️⃣ **Recognize and Mark Attendance**  
- Click **Track Images** to recognize faces and log attendance.  
- Attendance is saved in `Attendance/Attendance_<date>.csv`.

---

## 🔮 Future Improvements
🚀 **Upgrade to Database Storage** – Implement MySQL or SQLite instead of CSV.  
🤖 **Enhance Face Recognition Accuracy** – Utilize deep learning models.  
🌍 **Web-Based Interface** – Extend functionality with a browser-based UI.

---

## 👨‍💻 About the Developer
This project was developed by **Kumar Aryan**, a passionate **Software Developer** with expertise in **Python, Java, Machine Learning, and Full-Stack Development**. He specializes in **OpenCV, AWS Cloud Computing, and UI/UX Design**.

💡 **Explore More Projects**: [GitHub Profile](https://github.com/Arax007?tab=repositories)

---

## 📜 License
This project is licensed under the **MIT License**. See the **LICENSE** file for details.

