# Smart Attendance System using Face Recognition

## 📌 Overview

This project is a computer vision-based attendance system that uses face recognition to automatically identify individuals and mark their attendance.

## 🎯 Problem Statement

Manual attendance systems are time-consuming and prone to errors or manipulation. This project provides an automated solution using face recognition technology.

## 💡 Solution

The system detects and recognizes faces from images and marks attendance by storing the name and timestamp in a CSV file.

## 🛠️ Technologies Used

* Python
* OpenCV
* face_recognition library
* NumPy
* Pandas

## ⚙️ How to Run

1. Install required libraries:
   pip install -r requirements.txt

2. Add images to dataset folder

3. Run face encoding:
   python encode_faces.py

4. Run attendance system:
   python attendance.py

## 📊 Output

The attendance is stored in `attendance.csv` with name and timestamp.

## ⚠️ Note

* Dataset is not included due to size limitations.
* Users can add their own images in the dataset folder.

## 🚀 Future Improvements

* Real-time webcam integration
* GUI interface
* Cloud-based attendance storage
* Masked face detection

## 📚 Learnings

* Understanding of face detection and recognition
* Handling real-world dataset issues
* Debugging file handling and encoding errors

## 🧪 Sample Output

Screenshots of the system detecting faces and marking attendance are available in the `results/` folder.
