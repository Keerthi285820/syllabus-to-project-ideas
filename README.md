# 🎓 AI-Powered Syllabus-to-Industry Project Generator 🚀

> Convert university syllabus content into **industry-grade, resume-ready project ideas** using AI.

This project bridges the gap between **academic learning** and **real-world industry applications** by transforming syllabus topics into **role-specific, difficulty-aware, and buildable project ideas**.

---

## 📌 Why This Project?

Many students learn advanced concepts in college but struggle to:

* Convert syllabus topics into **practical projects**
* Align projects with **specific career roles**
* Find **real datasets** to actually build solutions

This tool solves that problem end-to-end.

---

## 💡 What This System Does

✔ Takes syllabus input in **any format**
✔ Extracts **clean, meaningful concepts**
✔ Generates **industry-aligned project ideas**
✔ Personalizes output by **role & difficulty**
✔ Exports results as **professional documents**

---

## ✨ Key Features

### 🧠 Intelligent Concept Extraction

* Uses **KeyBERT + Sentence Transformers**
* Cleans noisy syllabus text into canonical concepts

### 🎯 Project Generation Modes

* **Flagship Project** → One deep, end-to-end industry project
* **Multiple Projects** → 5–6 focused, resume-ready ideas

### 👨‍💻 Role-Based Customization (12+ Roles)

* Data Scientist
* ML Engineer
* AI Engineer
* Software Engineer
* Research Scientist
* Computer Vision Engineer
* NLP Engineer
* Robotics Engineer
* Data Analyst
* MLOps Engineer
* Full Stack Developer
* Product Engineer

### 📊 Difficulty Level Selection

* Beginner
* Intermediate
* Advanced

### 📂 Real Dataset Suggestions

* Kaggle datasets
* Government open data
* Research datasets

### 📄 Export Options

* Download as **PDF**
* Download as **DOCX**

### 🎨 Professional UI

* Built with **Streamlit**
* Clean, SaaS-style layout
* Optional dark mode

---

## 🛠️ Tech Stack

* **Python** – Core application logic
* **Streamlit** – Interactive web UI
* **KeyBERT** – Concept extraction
* **SentenceTransformers** – Semantic similarity
* **Groq LLM API** – Industry-grade project generation
* **Tesseract OCR** – Image-based syllabus input
* **pdfplumber** – PDF syllabus parsing
* **python-docx** – DOCX processing & export
* **FPDF** – PDF generation

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Keerthi285820/syllabus-to-project-ideas
cd syllabus-to-project-ideas
```

### 2️⃣ Install Dependencies

```bash
pip install streamlit keybert sentence-transformers groq pytesseract pillow pdfplumber python-docx fpdf
```

### 3️⃣ Install Tesseract OCR (Required for Image Input)

* Download from: [https://github.com/UB-Mannheim/tesseract/wiki](https://github.com/UB-Mannheim/tesseract/wiki)
* Add Tesseract to system PATH
* Verify:

```bash
tesseract --version
```

---

## 🔐 Environment Setup

Create a `.env` file:

```env
GROQ_API_KEY=your_groq_api_key_here
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```



---

## 📈 Why Recruiters Will Like This

✔ Shows **real-world problem solving**
✔ Demonstrates **NLP + LLM integration**
✔ Highlights **product thinking & UX**
✔ Projects are **customizable, realistic, and buildable**

This is not a generic academic project — it’s a **career-focused AI system**.

---

## 🔮 Future Enhancements

* Resume bullet generator
* Team collaboration mode
* Live dataset API integration
* Public SaaS deployment

---

## ⭐ Support

If you find this project useful:

* ⭐ Star this repository
* 🔗 Share it with students & peers

---

### 💬 Feedback Welcome

Would you use a tool like this to plan your projects?
Open an issue or start a discussion — contributions are welcome!

---

## 🔑 Key takeaways

* Converts syllabus → industry-ready projects automatically
* Fully personalized by role, difficulty, and depth
* Demonstrates strong AI + product engineering skills
* Ideal for resumes, portfolios, and final-year projects
