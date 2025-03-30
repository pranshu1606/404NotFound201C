# 404NotFound201C
The following is a project by 404NotFound in which we have tried to make a website that uses facial recognition and study patterns to form a personalised study material for the user
# Real-Time Facial Expression Recognition

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

