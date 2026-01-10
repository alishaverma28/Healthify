# 🧡 Healthify - AI Powered Personal Health Assistant 💙

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)  
[![Streamlit](https://img.shields.io/badge/Streamlit-1.28-orange?logo=streamlit&logoColor=white)](https://streamlit.io/)  
[![Gemini AI](https://img.shields.io/badge/Gemini_AI-red?logo=google&logoColor=white)](https://developers.generativeai.google/)

**Live Demo:** [Healthify App](https://your-streamlit-app-link.streamlit.app)  
**GitHub Repo:** [Healthify GitHub](https://github.com/alishaverma28/Healthify)

---

## 🌟 Project Overview

**Healthify** is an AI-powered personal health assistant that helps users make informed health decisions. Using **Google Gemini AI**, it provides **personalized guidance** based on user input, including age, gender, BMI, and fitness level. Users can ask health-related questions and get structured advice instantly.  

This project is built with **Python**, **Streamlit**, and **Google Generative AI (Gemini)**, making it **interactive, intelligent, and beginner-friendly**.

---

## 🏗️ Features

- Interactive **Streamlit** interface  
- Input user details: **Name, Gender, Age, Weight, Height, Fitness Level**  
- Automatic **BMI calculation**  
- AI-generated personalized health guidance including:
  - Comments on user details  
  - Problem analysis based on user query  
  - Possible causes  
  - Suggested solutions  
  - Recommended doctor/specialization if needed  
- Structured advice in **bullet points and tables**  
- Strictly **no medicine advice**  
- Designed for **educational purposes**  

---

## 💻 Installation

Follow these steps to set up and run **Healthify** locally:

1. **Clone the repository**

```bash
git clone https://github.com/alishaverma28/Healthify.git
cd Healthify
Create and activate a virtual environment

Windows:

bash
Copy code
python -m venv .venv
.venv\Scripts\activate
Linux/macOS:

bash
Copy code
python3 -m venv .venv
source .venv/bin/activate
Install required packages

bash
Copy code
pip install -r requirements.txt
Set up your API key

Create a .env file in the project root

Add your Google Generative AI key:

ini
Copy code
GOOGLE_API_KEY=your_api_key_here
Run the Streamlit app

bash
Copy code
streamlit run app.py
Open the app in your browser

Usually at http://localhost:8501

Live Demo (if deployed): Healthify App

🚀 Usage
Enter your personal details in the sidebar

Rate your fitness level (0-5 scale)

Type your health query

Receive structured guidance including:

Comments on your details

Problem analysis

Possible causes

Suggested solutions

Doctor specialization (if relevant)

Summary of advice

Note: Always consult a qualified doctor for medical conditions. This app provides informational guidance only.

🛠️ Code Overview
app.py: Main Streamlit application

requirements.txt: Python package dependencies

.env: Stores your Google API key (keep secret)

Main Logic:

Calculates BMI

Accepts fitness level input

Generates prompt for Google Gemini AI

Displays AI response in structured format

⚡ Technologies Used
Python 3.11

Streamlit for interactive UI

Pandas for BMI calculation

Google Generative AI (Gemini) for health advice

dotenv for secure API key management

🧑‍💻 Contributing
Fork the repository

Create a new branch

Make your improvements

Submit a pull request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgements
Streamlit

Google Generative AI

Python open-source libraries

💡 Future Improvements
Add charts for BMI trends

Allow multiple queries per session

Save user history for personalized tracking

Enhance UI design with Streamlit components
