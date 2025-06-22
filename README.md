
---

### 🌐 Static Website (`youtube-virality-predictor-site`) – `README.md`

# YouTube Virality Predictor – Static Frontend

This is the frontend for the YouTube Virality Predictor project. Users can upload a thumbnail and provide metadata (title, description, tags) to get a prediction from the backend API about their video's viral potential.

## 🌟 Features

- User-friendly interface
- Thumbnail resolution validation
- Displays API prediction response
- Fully static site deployable via GitHub Pages
- Utilizes a pre-trained research model to evaluate pre-published YouTube video metadata

## 🌐 Live

Accessible at: `https://rithikkulkarni.github.io/youtube-virality-predictor-site/`

## ⚙️ API Integration

The form submission sends a POST request to the backend FastAPI service deployed separately on Render:

js
fetch('https://your-api.onrender.com/extract_and_predict', {
  method: 'POST',
  body: formData
})

## 📁 Structure

├── index.html          # Main webpage

├── assets/             # CSS, JS

├── images/             # images

└── README.md

## 📌 Disclaimer

This tool offers an estimate of potential virality based on metadata. It is optimized to help creators avoid missing promising opportunities — some false positives are possible by design.
