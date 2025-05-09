# 🧠 ASCLEPIUS: AI-Powered Skin Condition Predictor

**ASCLEPIUS** is a full-stack web application that predicts potential skin conditions from uploaded images using machine learning. Built with modern technologies and deployed on Google Cloud Platform (GCP), it combines deep learning, REST APIs, and an interactive frontend to deliver real-time dermatological analysis.

---

## 🔬 Features

- 🖼️ **Image Upload & Analysis** — Upload skin images and receive condition predictions with confidence scores.
- 🧠 **AI Model** — Trained on dermatology datasets to detect multiple common skin conditions.
- 🌐 **Full Stack** — Built with Node.js / Express, React (or Vue), and MongoDB / Firestore.
- ☁️ **Cloud-Hosted** — Model hosted on GCP (Cloud Functions or Vertex AI); database and storage managed in the cloud.
- 📫 **API Tested** — Endpoints tested and documented with Postman.
- 🔐 **Authentication** — User login and image history secured with JWT / OAuth.

---

## 🧱 Tech Stack

| Layer         | Technologies                                   |
|---------------|------------------------------------------------|
| Frontend      | React / Vue, Tailwind CSS / Bootstrap          |
| Backend       | Node.js, Express.js                            |
| ML Model      | TensorFlow / PyTorch (converted to TF.js/ONNX) |
| Database      | MongoDB Atlas / Firestore                      |
| Cloud         | GCP: Cloud Functions, Cloud Run, Firestore     |
| API Testing   | Postman                                        |
| Deployment    | GCP, GitHub Actions / Docker                   |

---

## ⚙️ Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/vito-boni/ASCLEPIUS.git
cd ASCLEPIUS

# 2. Set up the backend
cd backend
npm install
# Add your .env variables (GCP credentials, DB URL, etc.)

# 3. Set up the frontend
cd ../frontend
npm install

# 4. Run the app
npm run dev  # or run frontend and backend separately
