📄 Resume Compatibility Analyzer
🔍 Project Overview
Resume Compatibility Analyzer is an AI-powered NLP application designed to evaluate the compatibility of a candidate’s resume with company job requirements. By analyzing textual features from resumes and job descriptions, the system ranks resumes based on their relevance and provides visual feedback on key skills, compatibility scores, and improvement suggestions.

This tool can be highly useful for:

Candidates to tailor their resumes effectively

Recruiters to shortlist resumes efficiently

Career platforms to automate resume-job matching

🚀 Key Features
📄 Resume and job description parsing using NLP

🧠 Keyword and skill extraction using TF-IDF, BERT, or spaCy

📊 Compatibility scoring using cosine similarity and ML models

🔍 Ranking of resumes based on job relevance

📈 Visualizations: skill match graphs, compatibility bar charts, top-k matches

🖥️ User Interface using Gradio or Streamlit for easy interaction

🧰 Tech Stack
Frontend: HTML, CSS, React.js / Streamlit / Gradio (for UI)

Backend: Python, Flask or Django

NLP Libraries: NLTK, SpaCy, Transformers (BERT)

ML Models: Logistic Regression, Random Forest, or fine-tuned BERT

Database: MongoDB or PostgreSQL (optional for storing resumes and results)

🗂️ Folder Structure
bash
Copy
Edit
resume-compatibility-analyzer/
│
├── data/                   # Sample resumes and job descriptions
├── src/                    # Core NLP logic
│   ├── extractor.py        # Extract keywords and entities
│   ├── matcher.py          # Match resumes with job requirements
│   ├── scorer.py           # Calculate compatibility scores
│   └── utils.py            # Helper functions
├── models/                 # Trained models or embeddings
├── app/                    # Gradio or Streamlit app
├── templates/              # Frontend templates (if using Flask)
├── requirements.txt
└── README.md
⚙️ How to Run
Clone the repo

bash
Copy
Edit
git clone https://github.com/your-username/resume-compatibility-analyzer.git
cd resume-compatibility-analyzer
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Launch the app

bash
Copy
Edit
streamlit run app/app.py
OR for Gradio:

bash
Copy
Edit
python app/app.py
🧪 Evaluation Metrics
✔️ Accuracy, Precision, Recall, F1 Score (for ML classification models)

🔢 Cosine Similarity Score (for text match)

📊 Top-K Resume Match Accuracy

📈 MAP (Mean Average Precision)

📉 Confusion Matrix

📌 Use Case Example
Upload your resume and select a company or paste a job description. The system will:

✅ Extract key skills from both documents
✅ Compare and calculate compatibility score
✅ Show visual graphs of matched vs missing skills
✅ Recommend resume improvements
✅ Display top companies or roles suited to your resume
