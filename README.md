# AI-ML-based Attendance Management System

An intelligent, face-recognition-based attendance management system built using Python, OpenCV, Tkinter GUI, and MySQL. This project automates student attendance through facial recognition, reducing manual effort and improving accuracy.

## 🔧 Features

- 🎓 **Student Management**: Add, update, and view student details.
- 🧠 **Face Training Module**: Captures face images and trains a recognizer using OpenCV's LBPH algorithm.
- 🤖 **Real-time Face Recognition**: Detect and recognize faces in real time to mark attendance.
- 📅 **Attendance Tracking**: View and export attendance data in CSV format.
- 🔐 **Login/Register System**: Secure access to the application with authentication.
- 🖼️ GUI designed with Tkinter and rich visual assets.

## 🗂️ Project Structure

```
AI-ML-based-Attendance-Management-System-main/
├── attendance.py            # Handles attendance marking and display
├── face_rec.py              # Face recognition logic
├── login.py                 # User login and dashboard routing
├── register.py              # Registration UI and backend
├── main.py                  # Main admin dashboard interface
├── student.py               # Student info management
├── train.py                 # Face data training module
├── attendance.csv           # Stores attendance records
├── haarcascade_frontalface_default.xml # OpenCV face detector
├── requirements.txt         # Python dependencies
├── Backgrounds/             # UI background assets
└── README.md                # Project documentation
```

## 🖥️ How It Works

1. **User logs in** using credentials.
2. **Student details** are registered and associated with face data.
3. **Face images are captured** and used to train a recognition model (LBPH).
4. **Real-time recognition** marks attendance and logs it in `attendance.csv`.

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/AI-ML-based-Attendance-Management-System.git
cd AI-ML-based-Attendance-Management-System-main
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

Make sure you also have:
- Python 3.8+
- OpenCV (`cv2`)
- MySQL (with a database and table set up for user and student info)

### 3. Run the App

```bash
python login.py
```

## 🛠️ Technologies Used

- Python
- OpenCV
- Tkinter
- MySQL
- PIL (Pillow)

## 🛡️ Security Note

- Always secure your database credentials.
- Consider encrypting stored passwords.

## 📸 Screenshots

> UI backgrounds and face recognition views are supported via assets in the `Backgrounds/` folder.

## 📄 License

This project is open source under the [MIT License](LICENSE).

## 🙌 Credits

Developed as part of an academic AI/ML automation project.
