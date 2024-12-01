# Face Recognition Attendance System

This repository contains a Machine Learning-based **Face Recognition Attendance System** built with Python. It enables automated attendance tracking using facial recognition.

## Research
This project is based on research published in IAEME:

- **Title**: *ATTENDANCE SYSTEM USING FACE
RECOGNITION AND RASPBERRY PI – REVIEW*  
- **Authors**: Ansari Mohammed Sajjad  
- **Journal/Conference**: IAEME  
- **Publication Date**: 2023-04-03  
- **Abstract**: The current attendance procedure is manual. Both professors and students lose a
lot of time as a result. Wait times for students increase when attendance is manually
recorded. Human mistake is closely linked to manual labor. Every person's face serves
as important, recognizable proof. Therefore, automating the attendance procedure will
increase learning time in the classroom. To make facial recognition accessible to
everyone, we picked the Raspberry Pi. A Raspberry Pi-based facial recognition system
using traditional facial recognition and recognition mechanisms is provided. For
security and surveillance purposes, facial recognition is crucial. Therefore, a system
that is effective and affordable is needed. Face recognition is the foundation of the
identification process, which is then broken down into the following three steps: face
recognition, feature extraction and classification, and real-time detection. It is
acknowledged that facial recognition is a crucial stage in our system. This system is
implemented in Python using the OpenCV library.

- **Link to Publication**: [Access the full research paper here](https://iaeme.com/Home/article_id/IJIDS_01_01_001)




---

## Features
- Real-time face recognition.
- User-friendly interface.
- Automated attendance tracking and record storage.
- Database support with SQLite3.
- Interactive UI built with HTML, CSS, and JavaScript.

---

## Technologies Used
- **Python**: Backend logic and ML implementation.
- **OpenCV**: For face detection and recognition.
- **SQLite3**: Database for attendance records.
- **HTML/CSS/JavaScript**: Frontend interface.
- **Django**: Framework for web application development.

---


---

## Installation

### Prerequisites
- Python 3.7 or later
- Django 3.0 or later
- OpenCV

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```
2. Create a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows: `env\Scripts\activate`
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Apply migrations:
    ```bash
    python manage.py migrate
    ```
5. Run the server:
    ```bash
    python manage.py runserver
    ```

---

## Usage
1. Start the server and navigate to `http://127.0.0.1:8000/` in your web browser.
2. Upload images for registration.
3. Use the interface to track attendance.

---

## Contributing
Contributions are welcome! Please create a pull request for proposed changes or fixes.

---





