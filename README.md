
# 🍃 FoodBridge – Food Sharing & Waste Reduction Platform


**FoodBridge** is a full-stack web application that helps reduce food waste by connecting individuals and organizations with excess food to local NGOs and charities. Using AI-powered expiry date detection, real-time notifications, and geolocation, FoodBridge streamlines food sharing and redistribution for a more sustainable community.
##✨ Features

---

-🧠 **AI Expiry Date Detection**
Upload a photo of a food package, and FoodBridge automatically detects the expiry date using Google Cloud Vision API.

-☁️ **Cloud Firestore Database**
Securely stores food item data, user emails, and notification status in Google Cloud Firestore.

-📧 **Automated Email Notifications**
Users receive email alerts about expiring food items via EmailJS.

-🗺️ **NGO Map Integration**
View nearby NGOs and charities on an interactive map using Google Maps and Places APIs.

-🚀 **Full-Stack Deployment**
Both backend and frontend are served from a single Flask application, deployed on Railway.

## 🛠️ Tech Stack
- Frontend: HTML, CSS, JavaScript (with Firebase and EmailJS SDKs)
- Backend: Python, Flask
- Database: Google Cloud Firestore
- AI Service: Google Cloud Vision API
- Email Service: EmailJS
- Maps: Google Maps JavaScript API, Places API
- Deployment: Railway


## 🚦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/caira-neha/FoodBridge.git
cd FoodBridge
```

### 2. Set Up Environment Variables

Create a .env file in the backend/ directory and add your credentials:

GOOGLE_APPLICATION_CREDENTIALS_JSON=your_service_account_json
FIREBASE_API_KEY=your_firebase_api_key
FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
FIREBASE_PROJECT_ID=your_firebase_project_id
FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
FIREBASE_APP_ID=your_firebase_app_id
GOOGLE_MAPS_API_KEY=your_google_maps_api_key
EMAILJS_USER_ID=your_emailjs_user_id
EMAILJS_SERVICE_ID=your_emailjs_service_id
EMAILJS_TEMPLATE_ID=your_emailjs_template_id

### 3.Install Dependencies

```bash
cd backend
pip install -r requirements.txt
```

### 4. Run the Application Locally
```bash
python main.py
```

## Deployment

- Add all environment variables in the Railway dashboard.

- The Procfile is already set up for Flask.

- Deploy the project to Railway.

### 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

### 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

### 🙏 Acknowledgements


- Google Cloud
- Firebase
- EmailJS
- Railway

---
