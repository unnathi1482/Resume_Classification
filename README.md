
# 📄 Resume Classification

Resume Classification is an AI-powered tool that automatically analyzes and classifies resumes into relevant job categories. It’s designed to help recruiters, HR teams, and hiring managers quickly sort resumes, identify suitable candidates, and streamline the recruitment process.

---

 ✨ Features

* Upload resumes in PDF or DOCX format
* Automatically classify resumes into job categories
* Provides insights into resume content, such as skills and experience
* Fast and user-friendly web interface for effortless interaction
* Machine learning-based for accurate predictions

---
 🖥 How It Works

1. The user uploads a resume.
2. The system processes the text using natural language processing techniques.
3. The trained machine learning model predicts the most relevant job category.
4. Users can view the classification results instantly and make informed hiring decisions.

---

⚡ Quick Start

1. Clone the repository:

```bash
git clone https://github.com/unnathi1482/Resume_Classification.git
cd Resume_Classification
```

2. (Optional) Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the app:

```bash
streamlit run app.py
```

---

 🛠 Tech Stack

* Python – Core programming language
* Scikit-learn – Machine learning model development
* Streamlit – Interactive web app interface
* NLTK / SpaCy – Text preprocessing and NLP

---

 📁 Project Structure

```
Resume_Classification/
│
├── app.py           # Streamlit interface
├── model.py         # ML model scripts
├── requirements.txt # Dependencies
├── data/            # Dataset for training/testing
└── saved_model/     # Trained model files
```

---

