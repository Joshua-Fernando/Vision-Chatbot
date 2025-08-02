# Vision-Chatbot

## Description

The Vision Chatbot is an intelligent web application that analyzes images based on your questions. Powered by Azure AI's multimodal capabilities, this app allows you to upload an image, ask a question about it, and receive a detailed, context-aware answer from an advanced AI model.
Built with a Flask backend, this project serves as a practical demonstration of how to integrate sophisticated vision and language models into your applications. It's a perfect starting point for developers interested in building applications for image interpretation, visual question answering, and interactive AI experiences.

---

## Features
- mage Upload: Easily upload any image file for analysis.
- Text Prompts: Ask specific questions or give instructions related to the uploaded image.
- AI-Powered Analysis: Get detailed, conversational responses from an AI assistant that understands both the image and your text prompt.
- Simple Web Interface: A clean and straightforward user interface for interacting with the chatbot.


---

##  Tech Stack
- **Python 3.11+**
- **Flask** (for the web interface)
- **Azure AI Vision Service**


--- 

##  Project Structure
```
├── app.py                     # Flask web application
├── vision_chatbot.py          # Core logic for interacting with Azure AI
├── templates/
│   └── index.html             # Web interface template
├── static/
│   ├── uploads/               # Directory for user-uploaded images
│   └── style.css              # Styles for the web interface
├── requirements.txt           # Python dependencies
├── .env                       # Environment variables
├── README.md
└── LICENSE                 


```

---

## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Joshua-Fernando/Vision-Chatbot
cd Vision-Chatbot
```

### 2. Install Dependencies
Using **pip**:
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

---

## Azure AI Language Setup
1.Create an Azure AI Project resource in the Azure portal.
2. Within your project, deploy a model that supports vision and chat completions.
3. Navigate to your project's settings to get the following credentials:
3. Get the following credentials:
   - **Project Endpoint**
   - **Model Deployment Name**
 
4. Add these to your environment variables:
   ```bash
   
    PROJECT_CONNECTION="your_project_endpoint"
    MODEL_DEPLOYMENT="your_model_deployment"

   ```

---

## Running the Web App
```bash
python app.py
```
Then open your browser and navigate to:
```
http://localhost:5000
```

---

## Deployment
You can deploy this project to:
- **Azure App Service**
- **Replit**
- **Heroku**
- **Any cloud hosting that supports Flask**

---

## License
This project is licensed under the **Apache-2.0 license**.

---

### 👨‍💻 Author
Developed by **Joshua Fernando**  
Feel free to contribute or open issues!

