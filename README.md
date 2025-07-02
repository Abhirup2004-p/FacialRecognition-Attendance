# Facial Recognition Attendance System

A real-time facial recognition attendance system built using Python and OpenCV. This project automates the process of taking attendance by identifying faces from a webcam feed and logging them with a timestamp into a CSV file.

---

## 🔍 Features

* Real-time face detection and recognition using webcam
* Attendance logging with name, date, and time
* Saves records in a CSV file for easy tracking
* Easy-to-use, lightweight Python application

---

## 🛠️ Tech Stack

* **Language:** Python
* **Libraries/Tools:**

  * OpenCV
  * face\_recognition
  * NumPy
  * CSV module
  * datetime

---

## 📁 Project Structure

```
face-recognition-attendance/
│
├── attendance.csv               # Stores attendance logs
├── main.py                      # Main script to run the application
├── images/                      # Folder containing reference images for known faces
└── README.md                    # Project documentation
```

---

## ▶️ How to Run

1. Clone this repository
2. Install dependencies:

   ```
   pip install opencv-python face_recognition numpy
   ```
3. Add known face images to the `images/` folder (use clear frontal photos, named as `Name.jpg`)
4. Run the application:

   ```
   python main.py
   ```
5. The webcam will start, detect faces, and log attendance into `attendance.csv`

---

## 📷 Sample Output

* [ ] Recognizes known faces
* [ ] Logs `Name`, `Date`, and `Time` to `attendance.csv`
* [ ] Skips duplicate entries on the same day

---

## 🚀 Future Improvements

* GUI for user interaction
* Face registration feature
* Integration with cloud storage or database
* Email/SMS notification for attendance summary

---

## 🤝 Contributing

Feel free to open issues or submit pull requests to improve the project.
