# 🧡 Healthify - AI Powered Personal Health Assistant 💙

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)  
[![Streamlit](https://img.shields.io/badge/Streamlit-1.28-orange?logo=streamlit&logoColor=white)](https://streamlit.io/)  
[![Gemini AI](https://img.shields.io/badge/Gemini_AI-red?logo=google&logoColor=white)](https://developers.generativeai.google/)

**Live Demo:** *(Add your Streamlit app link here)*  
**GitHub Repo:** [Healthify GitHub](https://github.com/alishaverma28/Healthify)

---

## 🌟 Project Overview

**Healthify** is an AI-powered personal health assistant that helps users make informed health decisions. Using **Google Gemini AI**, it provides **personalized guidance** based on user input, including age, gender, BMI, and fitness level. Users can ask health-related questions and get structured, professional advice instantly.  

Built with **Python**, **Streamlit**, and **Google Generative AI (Gemini)**, this project is **interactive, intelligent, and beginner-friendly**.

---

## 🏋️ Key Features

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

## 🏛️ Architecture

The Healthify system is structured to provide **efficient, AI-powered health guidance**:

1. **User Interface (UI)** - **Streamlit Sidebar and Input Fields**
   - Users enter their personal details (Name, Age, Gender, Weight, Height)  
   - Fitness level slider (0-5 scale)  
   - Text input for health queries

2. **BMI Calculation Module**
   - Converts height and weight into BMI  
   - Provides a real-time comment to users on BMI value

3. **Prompt Generation Module**
   - Takes user inputs and query  
   - Formats a detailed prompt for Google Gemini AI, including:
     - User details  
     - BMI  
     - Fitness rating  
     - Health query  
   - Ensures AI response is structured (bullets, tables, summary)

4. **AI Engine**
   - **Google Gemini AI** (Generative Model: `gemini-2.5-flash-lite`)  
   - Processes the prompt and returns personalized health advice

5. **Response Display Module**
   - Streamlit UI renders the AI-generated response  
   - Output includes:
     - Comments on details  
     - Problem analysis  
     - Possible causes  
     - Suggested solutions  
     - Doctor specialization (if relevant)  
     - Summary of recommendations

6. **Environment & Configuration**
   - **Python 3.11**  
   - **Packages:** Streamlit, pandas, dotenv, google-generativeai  
   - `.env` stores `GOOGLE_API_KEY` for secure API access

**System Flow Diagram (simplified):**

User Input → BMI Calculation → Prompt Generation → Google Gemini AI → AI Response → Streamlit UI Display


---

## 🚀 Usage

1. Enter your **personal details** in the sidebar  
2. Rate your **fitness level** (0-5 scale)  
3. Type your **health query**  
4. Receive structured guidance including:  
   - Comments on your details  
   - Problem analysis  
   - Possible causes  
   - Suggested solutions  
   - Doctor specialization (if relevant)  
   - Summary of advice  

**Note:** Always consult a qualified doctor for medical conditions. This app provides **informational guidance only**.

---

## 🛠️ Code Overview

- `app.py`: Main Streamlit application  
- `requirements.txt`: Python package dependencies  
- `.env`: Stores your Google API key (keep secret)  

**Main Logic:**

- Calculates BMI  
- Accepts fitness level input  
- Generates prompt for Google Gemini AI  
- Displays AI response in structured format  

---

## ⚡ Technologies Used

- Python 3.11  
- Streamlit for interactive UI  
- Pandas for BMI calculation  
- Google Generative AI (Gemini) for health advice  
- dotenv for secure API key management  

---

## 🧑‍💻 Contributing

- Fork the repository  
- Create a new branch  
- Make your improvements  
- Submit a pull request  

---

## 📄 License

MIT License

---

## 🙏 Acknowledgements

- [Streamlit](https://streamlit.io/)  
- [Google Generative AI](https://developers.generativeai.google/)  
- Python open-source libraries  

