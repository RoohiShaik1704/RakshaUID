# RakshaUID
RakshaUID is an advanced AI-powered identity verification platform designed to detect Aadhaar fraud. It combines Deep Learning (CNN), Optical Character Recognition (OCR), and Biometric Face Verification into a strict three-stage security workflow to ensure that only authentic identities are verified.

Key Features

🔍 Three-Stage Verification Workflow

Document Analysis:
Uses a trained CNN model (TensorFlow) to distinguish valid Aadhaar cards from non-Aadhaar documents.

Biometric Face Matching:
Uses OpenCV (LBPH Face Recognizer) to match the photo on the ID card with a live webcam feed or an uploaded user image.

Data Extraction & QR Validation:
Extracts text using PaddleOCR and cross-verifies it with decoded QR code data to ensure consistency.

🤖 Fraud Detection Engine
Analyzes image forensics (tampering traces), data consistency, and ML-based fraud probability scores.

📂 Secure Database
Stores verified records in SQLite for quick future lookups and duplicate identity prevention.

💻 Interactive Dashboard
A modern, responsive web interface built with FastAPI and JavaScript, featuring Dark/Light mode and real-time verification status updates.

🛠️ Tech Stack
Backend: Python 3.10+, FastAPI, Uvicorn
Deep Learning: TensorFlow / Keras (CNN Classification)
Computer Vision: OpenCV (opencv-contrib-python), PaddleOCR
Machine Learning: Scikit-Learn (Random Forest for Fraud Probability)
Database: SQLite
Frontend: HTML5, CSS3, JavaScript (Fetch API)
