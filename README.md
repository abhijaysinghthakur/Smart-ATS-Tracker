# Smart-ATS-Tracker

An AI-powered tool for resume screening and alignment with job descriptions, built using Streamlit and Google’s Generative AI.  
Designed to help job-seekers and recruiters automatically assess how well a resume matches a job role, highlight missing keywords, and produce summarized feedback.

---

## 🚀 Features

- Upload a PDF resume and paste a job description; the app outputs a structured evaluation (match %, missing keywords, profile summary).  
- Uses Google Generative AI (Gemini Pro) to generate response from a prompt template.  
- PDF parsing via **PyPDF2**.  
- Interactive web UI built with **Streamlit** for ease of use.  
- Environment-based API configuration using **dotenv**.

---

## 🧰 Tech Stack & Tools

- **Programming Language**: Python  
- **Web Interface / UI**: Streamlit  
- **AI / LLM API**: Google Generative AI (Gemini Pro)  
- **PDF Parsing**: PyPDF2  
- **Environment Management**: python-dotenv  
- **Data Format**: JSON (for structured output)  

---

## 📂 Project Structure

Smart-ATS-Tracker/

- `app.py` : Main Streamlit application where the ATS tracking logic runs.  
- `requirements.txt` : Python dependencies required to run the project.  
- `README.md` : Project documentation (this file).  
- `.env (example)` : Sample environment variables file (should not be committed to repo)
