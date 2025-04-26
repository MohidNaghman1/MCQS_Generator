# MCQ Generator App

This is a Flask web application that automatically generates multiple-choice questions (MCQs) from uploaded documents (PDF, DOCX, or TXT files).

The app extracts text from the uploaded file, generates MCQs using an AI model, and allows users to download the questions as `.txt` or `.pdf` files.

---

#  How It Works

Upload your document.

Enter how many MCQs you want.

The app reads the file, sends the text to an AI model, and creates MCQs.

You can download the MCQs as .txt or .pdf!

## 🚀 Features

- Upload a `.pdf`, `.docx`, or `.txt` file
- Choose how many MCQs you want
- Automatically generate MCQs using AI
- Download generated MCQs as a **Text file** or **PDF file**

---

## 🛠️ Technologies Used

- Python
- Flask
- pdfplumber (for reading PDFs)
- python-docx (for reading DOCX files)
- FPDF (for creating PDFs)
- Google Generative AI (for MCQ generation)
- python-dotenv (for environment variables)

---

## 📂 Project Structure

/MCQS-generator-flask-app               # Root directory
    /uploads                           # Folder to store uploaded files
    /results                           # Folder to store generated MCQs
    /templates                         # HTML templates for rendering pages
        index.html                     # Main page with upload form
        results.html                   # Page to display results and d
    app.py                              # Main Flask application file
    requirements.txt                    # Python dependencies file
    .env                                # Environment variables (keep secret API keys, etc.)
    README.md                           # Project documentation (this file)


# Important Notes
.env and myenv/ folders should be added to .gitignore to avoid uploading them to GitHub.

If using Google AI, make sure your API Key is stored safely in .env and not shared publicly.

