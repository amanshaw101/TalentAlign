# TalentAlign 

**TalentAlign** is an intelligent resume analyzer and matcher web application built using **Flask** and **NLP (Natural Language Processing)**. It allows users to upload multiple resumes and a job description, then ranks the resumes based on how well they match the job description using **TF-IDF vectorization** and **cosine similarity**.

---

## 🔍 Features

- 📄 **Supports Multiple Resume Formats**: PDF, DOCX, TXT
- 🤖 **NLP-Based Matching**: Uses TF-IDF and cosine similarity to match resumes with a job description.
- 📈 **Ranking System**: Displays the top 3 resumes most relevant to the job description.
- 🌐 **Simple Web Interface**: Built with Flask for easy usability.

---

## 💡 How It Works

1. A job description is entered into a form.
2. One or more resumes are uploaded in supported formats.
3. The app extracts the text content from each resume.
4. TF-IDF vectorization is applied to both the job description and resumes.
5. Cosine similarity scores are calculated to find the most relevant resumes.
6. The top 3 matches are displayed on the web interface.

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Text Processing**: PyPDF2, docx2txt, scikit-learn 
- **Frontend**: HTML 
- **Other**: OS, File handling

