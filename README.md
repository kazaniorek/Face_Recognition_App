
# Face Recognition App with Alert Emails

This project implements a real-time face recognition application using OpenCV and face_recognition libraries, with an added feature of sending email alerts when a recognised face is detected. 
It demonstrates the use of computer vision, image processing, and basic automation.

## Features

- Real-time face detection and recognition using webcam
- Automatic email alerts with screenshots when a known face is detected
- Customisable list of known faces
- Live annotation of recognised individuals on video stream

## Technologies

- Python
- OpenCV
- face_recognition
- smtplib for email alerts
- NumPy

## How to Run

1. Install required libraries:
   ```bash
   pip install opencv-python face_recognition numpy
   ```

2. Configure the script with:
   - Your email credentials (for sending alerts)
   - Reference images of known individuals

3. Run the notebook:
   - `Face_recognition_app_with_alert_emails.ipynb`

## Author

Mariusz Sołtycz

---

This project was completed as part of my BSc Artificial Intelligence degree and showcases applied computer vision and automation in a security context.
