![WhatsApp Image 2025-03-30 at 08 19 19_0dabc047](https://github.com/user-attachments/assets/b05813fa-4aad-40c4-8730-d6e9daea77e7)# 404NotFound201C
The following is a project by 404NotFound in which we have tried to make a website that uses facial recognition and study patterns to form a personalised study material for the user
# Real-Time Facial Expression Recognition

![Uploading ![WhatsApp Image 2025-03-30 at 08 19 19_99b59df3](https://github.com/user-attachments/assets/8ee884ef-3670-4660-9f6a-304f097a4de1)![WhatsApp Image 2025-03-30 at 08 19 18_874faa7d](https://github.com/user-attachments/assets/3e8770d9-e54a-4214-b828-fce29668be9c)
![WhatsApp Image 2025-03-30 at 08 19 19_e80b51f6](https://github.com/user-attachments/assets/ee9c8399-e767-432f-a69d-ba0a1d5cd48e)
![WhatsApp Image 2025-03-30 at 08 19 19_c657518e](https://github.com/user-attachments/assets/f78d2db8-419d-44f7-b5b0-783a232ce6db)
![WhatsApp Image 2025-03-30 at 08 19 19_60d283a6](https://github.com/user-attachments/assets/8d7cae34-1eb5-4a17-b7aa-ec67d8e3cb51)
![WhatsApp Image 2025-03-30 at 08 19 18_52c34b63](https://github.com/user-attachments/assets/ddb8df4d-6bce-42b5-acbf-1bffb29d71c7)
![WhatsApp Image 2025-03-30 at 08 19 18_5acdbe93](https://github.com/user-attachments/assets/d64e975f-477f-4a2b-a004-1b89605f2f5a)
![WhatsApp Image 2025-03-30 at 08 19 18_c4135dd9](https://github.com/user-attachments/assets/87e573a3-2d76-4347-81f7-743994a83b3e)


## Overview
This project implements real-time facial expression recognition using a convolutional neural network (CNN) model. The system detects human emotions from live webcam feeds and classifies them into one of seven categories:

- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

The project integrates a **TypeScript (TSX) frontend** with a **Flask backend** for real-time inference.

## Features
- Real-time facial emotion detection
- Web-based interface using TypeScript (React/Next.js)
- Backend powered by Flask and OpenCV
- WebSocket-based communication between frontend and backend

## Tech Stack
### Frontend:
- TypeScript (TSX)
- React
- WebRTC API for webcam access
- WebSocket for real-time communication

### Backend:
- Python (Flask)
- OpenCV for face detection
- TensorFlow/Keras for deep learning
- WebSockets for real-time data streaming

## Installation
### Prerequisites
- Node.js & npm (for frontend)
- Python 3.x (for backend)
- Virtual environment (recommended)
- OpenCV, TensorFlow, Flask, Flask-SocketIO

### Clone the Repository
```bash
git clone https://github.com/your-username/real-time-facial-expression-recognition.git
cd real-time-facial-expression-recognition
```

### Backend Setup
```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
python app.py
```

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

## Usage
1. Start the backend server using `python app.py`.
2. Start the frontend using `npm run dev`.
3. Open `http://localhost:3000` in your browser.
4. Grant camera permissions.
5. See real-time emotion predictions from the webcam.

## Folder Structure
```
real-time-facial-expression-recognition/
│── backend/  # Flask backend
│   ├── app.py  # Main Flask application
│   ├── model/  # Pre-trained facial expression model
│   ├── requirements.txt  # Python dependencies
│
│── frontend/  # React frontend
│   ├── pages/
│   ├── components/
│   ├── tsconfig.json
│   ├── package.json
│
│── README.md  # Project documentation
```

## Future Enhancements
- Improve accuracy with a larger dataset
- Deploy as a cloud-based service
- Support mobile browsers
- Add more detailed emotion analytics

## License
This project is open-source and available under the MIT License.

## Contributors
- **Name** - Pranshu Thakkar, Om Tekriwal, Chaitanya Pandey, Anushka Mishra

Feel free to contribute! Fork the repo and submit pull requests.

