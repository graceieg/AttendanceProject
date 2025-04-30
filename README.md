
## 🚀 How It Works

1. The script loads images from the `ImagesAttendance` directory.
2. It encodes the faces using `face_recognition`.
3. When the webcam detects a face, it compares it to known encodings.
4. If a match is found, the name is displayed and logged in `Attendance.csv`.

## ✅ How to Run

1. Clone the repository or download the files.
2. Add images of known people to the `ImagesAttendance/` folder.
3. Make sure Python and the required packages are installed:
    ```bash
    pip install opencv-python face_recognition numpy
    ```
4. Run the script:
    ```bash
    python AttendanceProject.py
    ```
5. When a known face is detected via webcam, it will be logged in `Attendance.csv`.

## 🛡 Safety & Limitations

- The system uses the first detected face encoding per image; if multiple faces exist in one photo, it only encodes the first.
- Accuracy depends on lighting and webcam quality.

## ✍️ Author

Grace Giebel  
Python Face Recognition Project — 2025  
