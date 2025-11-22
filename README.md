**📂 Project Structure**

resume_based_job_recommendation/
│── data/
│   ├── job_descriptions.csv
│   ├── sample_resumes/
│
│── src/
│   ├── preprocess.py
│   ├── vectorize.py
│   ├── recommender.py
│   ├── app.py (optional API)
│
│── README.md
│── requirements.txt


**How It Works**

User uploads a resume file.

System extracts and cleans the resume text.

Job descriptions are vectorized using TF-IDF.

Cosine similarity scores are calculated.

Top recommended job roles are displayed.

**📦 Installation**
pip install -r requirements.txt

**▶️ Run the Project**
Option 1: Run the Script
python recommender.py

Option 2: Run API
python app.py

**📨 Output**

The system returns:

Best matching job titles

Similarity score for each job

Recommended skills and insights

**🧠 Future Enhancements**

Integration with real-time job portals

Deep learning-based embeddings (BERT, SBERT)

Resume auto-parsing for name, email, skills extraction

Dashboard UI
