# Harvestify 🌱  
### AI-Powered Plant Health Assistant

![Harvestify Banner](./Web%20App%20Interface.png)

Harvestify is an AI-powered web application designed to help farmers, gardeners, and agricultural enthusiasts monitor and improve plant health through intelligent disease detection and crop management recommendations.

By leveraging machine learning and computer vision technologies, Harvestify enables users to upload plant leaf images and receive instant disease diagnosis, treatment suggestions, fertilizer recommendations, and crop guidance based on environmental conditions.

---

# 🚀 Features

## 🌿 Plant Disease Detection
Upload a plant leaf image and receive:
- Disease prediction
- Confidence analysis
- Treatment recommendations
- Preventive guidance

## 🌾 Crop Recommendation
Get smart crop suggestions based on:
- Soil conditions
- Weather data
- Environmental factors

## 🧪 Fertilizer Recommendation
Receive personalized fertilizer suggestions to:
- Improve crop yield
- Enhance plant growth
- Maintain soil health

## ⚡ Real-Time AI Analysis
Fast and accurate AI-powered predictions with responsive performance.

## 🎨 User-Friendly Interface
Clean and intuitive interface designed for ease of use across all user levels.

---

# 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### Machine Learning
- TensorFlow
- Scikit-learn
- ResNet50

### Database & Storage
- Pickle Models
- HDF5 Models

### Cloud & Deployment
- Microsoft Azure

---

# 📦 Installation

## 1. Clone the Repository

```bash
git clone https://github.com/MGJillaniMughal/Harvestify-AI-Powered-Plant-Health-Assistant.git
```

## 2. Navigate to the Project Directory

```bash
cd Harvestify-AI-Powered-Plant-Health-Assistant
```

## 3. Create a Virtual Environment (Optional but Recommended)

### Windows
```bash
python -m venv venv
venv\Scripts\activate
```

### macOS / Linux
```bash
python3 -m venv venv
source venv/bin/activate
```

## 4. Install Dependencies

```bash
pip install -r requirements.txt
```

## 5. Configure Environment Variables

Create a `.env` file in the root directory and add the required configuration values:

```env
SECRET_KEY=your_secret_key
API_KEY=your_api_key
```

---

# ▶️ Running the Application

Start the Flask development server:

```bash
python app.py
```

The application will be available at:

```bash
http://localhost:5000
```

---

# 📸 How to Use

1. Open the application in your browser.
2. Navigate to the **Disease Detection** section.
3. Upload a plant leaf image.
4. Submit the image for analysis.
5. View disease predictions and treatment recommendations instantly.

---

# ☁️ Deployment

Harvestify is deployed on Microsoft Azure:

🌐 Live Demo:  
https://salmon-river-0feb8641e.5.azurestaticapps.net/

## Azure Deployment Overview

The application can be deployed using:
- Azure App Service
- GitHub Actions
- Azure DevOps
- ZIP or FTP deployment

### Deployment Steps

1. Create an Azure App Service
2. Configure Python runtime
3. Add environment variables
4. Deploy application source code
5. Install dependencies from `requirements.txt`

---

# 📁 Project Structure

```plaintext
Harvestify-AI-Powered-Plant-Health-Assistant/
│
├── static/
│   ├── css/
│   ├── images/
│   └── js/
│
├── templates/
│   ├── index.html
│   ├── crop.html
│   ├── fertilizer.html
│   ├── disease.html
│   ├── crop-result.html
│   ├── fertilizer-result.html
│   └── disease-result.html
│
├── models/
│   ├── resnet50_model.h5
│   ├── RandomForest.pkl
│   └── ...
│
├── app.py
├── requirements.txt
└── README.md
```

---

# 🤝 Contributing

Contributions are welcome and appreciated.

# 🙌 Acknowledgements

Special thanks to:
- Open-source contributors
- TensorFlow and Scikit-learn communities
- Agricultural AI research communities
- Everyone supporting AI innovation in agriculture

---

# 🌱 Harvestify

Empowering smarter agriculture through AI-driven plant health intelligence.

