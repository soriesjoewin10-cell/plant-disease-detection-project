🌿 PlantGuard AI – Plant Disease Detection System

PlantGuard AI is a deep learning–based web application that detects plant leaf diseases from images.
The system uses a TensorFlow/Keras CNN model for disease classification and a modern React frontend for user interaction.

This project is designed as an end-to-end AI application, covering frontend, machine learning, backend API, and deployment.

🚀 Features

📷 Upload plant leaf images

🔍 Detect plant diseases automatically

📊 Display disease name with confidence score

⚡ Fast and responsive UI

🌐 Web-based application

🧠 Deep Learning powered (CNN)

🛠️ Tech Stack
Frontend

React (TypeScript)

Vite

Tailwind CSS

Machine Learning

TensorFlow

Keras

Convolutional Neural Networks (CNN)

Transfer Learning (MobileNetV2)

Backend (Phase 2)

Python

FastAPI / Flask

REST API

Deployment

Frontend: Vite (Local) / Vercel / Render

Backend: Render (Free Tier)

📂 Project Structure
plant-disease-detection-project/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.ts
│
├── backend/
│   ├── app.py
│   ├── model/
│   │   └── plant_disease_model.keras
│   └── requirements.txt
│
└── README.md

🧠 Model Overview

The disease detection model is built using TensorFlow and Keras

Uses CNN with transfer learning

Model trained locally using GPU acceleration (NVIDIA RTX 3050) / Google Colab

Input size: 224 × 224

Output: Disease class + confidence score

🧪 Dataset

Publicly available PlantVillage dataset

Contains healthy and diseased plant leaf images

Images are preprocessed and resized before training

▶️ How to Run the Project (Frontend)
1️⃣ Install dependencies
npm install

2️⃣ Start development server
npm run dev

3️⃣ Open in browser
http://localhost:5173

🔌 Backend API (Phase 2 – Planned)

Accepts image via POST request

Loads trained Keras model

Returns JSON response:

{
  "disease": "Early Blight",
  "confidence": 0.92
}

🎯 Project Phases
✅ Phase 1 – Frontend

UI design

Image upload & preview

Dummy prediction flow

🔄 Phase 2 – Machine Learning & Backend

CNN model training

API development

Model integration

🚀 Phase 3 – Deployment

Backend deployment on Render

Frontend deployment

End-to-end testing

📌 Applications

Smart agriculture

Early disease detection

Crop health monitoring

Decision support for farmers

🧑‍🎓 Academic Note

This project was developed as part of a Neural Networks / Deep Learning academic project, following best practices in machine learning and web application development.

👨‍💻 Author

Joewin Sories
B.E. Computer Science & Engineering
Specialization: Artificial Intelligence / Machine Learning

If you want, I can also:

✨ Make a shorter README

📄 Convert this into a project report

🧠 Add model training explanation

🚀 Add deployment section with Render

Just tell me 👍
