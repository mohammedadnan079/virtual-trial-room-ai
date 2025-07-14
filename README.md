# virtual-trial-room-ai
AI-powered Virtual Trial Room that lets users try on clothes using image processing &amp; ML.

# 🧥 Virtual Trial Room (VTR) – AI-Powered Try-On System

The **Virtual Trial Room** is a smart, AI-powered web application that enables users to **virtually try on clothes** by uploading or capturing their image. The system uses image processing and basic machine learning techniques to overlay selected garments on the user's photo — providing a virtual fitting room experience from the comfort of home.

---

## 📌 Key Features

- 👤 **User Authentication**: Sign up / Log in functionality
- 📷 **Upload or Capture Photo**: Upload an image or take a photo with your webcam
- 👕 **Try On Clothes Virtually**: Select a shirt/top from the catalog to try on
- 🎯 **Clothing Overlay**: Overlay selected clothing on user image using OpenCV/PIL
- 📐 **Body Measurement Support** *(Upcoming)*: Improve fit using user-input measurements
- ⚧️ **Gender-based Clothing Filtering**: View clothes tailored to user's gender
- 💾 **Data Storage**: Store try-on history and user profiles in a connected database

---

## 🧱 Tech Stack

| Layer         | Technologies Used                  |
|---------------|------------------------------------|
| Frontend      | HTML, CSS, JavaScript              |
| Backend       | Python (Flask or Django)           |
| Image Processing | OpenCV / PIL                     |
| Database      | SQLite / MongoDB (for scaling)     |
| ML/AI Model   | Basic ML logic for image overlay   |
| Hosting       | Localhost (Dev) / Render, Heroku (Live) |

---

## 🛠️ How It Works

1. User registers and logs into the app.
2. User uploads or captures an image using a webcam.
3. The app shows a catalog of available clothes.
4. Upon selecting an item, the system overlays the selected garment on the user's image.
5. Future versions will use body measurements or generate avatars for better realism.

---

## 📷 Image Overlay Example

> *(You can add demo screenshots or GIFs here once available)*

---

## 🚀 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/virtual-trial-room-ai.git
cd virtual-trial-room-ai
```
## 2. Install Dependencies

pip install -r requirements.txt

## 3. Run the App
python app.py
### Navigate to http://localhost:5000 to use the app in your browser.

## 📁 Folder Structure
virtual-trial-room-ai/
├── static/               # CSS, JS, and image assets
├── templates/            # HTML templates
├── uploads/              # Uploaded user photos
├── clothes/              # Sample clothing images
├── app.py                # Main application script
├── requirements.txt      # Python dependencies
└── README.md

## 🙌 Contributors
Mohammed Adnan – Project Lead

Open to collaboration! Feel free to fork and contribute.

