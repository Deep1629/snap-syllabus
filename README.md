# SnapSyllabus 📘✨

**SnapSyllabus** is a tool that extracts the *actual useful info* from academic syllabi — no fluff, no filler.

Upload a syllabus PDF, and get back just what you need:
- 🧑‍🏫 Instructor and TA names
- 📧 Contact info (emails)
- 📝 Grading breakdowns (assignment types + weights)
- 📚 Required materials
- 🛑 Key policies (late work, attendance, etc.)

---

## 🎯 Problem

College syllabi are usually 10+ pages of cluttered, inconsistent formatting. Students waste time digging through documents every semester just to find simple info like grading schemes or professor emails.

---

## 💡 Solution

SnapSyllabus lets students drop in a syllabus and immediately get a clean, structured summary of the most important details.

No AI hallucinations, no wall of text — just raw facts extracted fast.

---

## 🔨 Tech Stack

- **Backend**: Python (Flask or FastAPI)
- **PDF Parsing**: PyMuPDF, Regex, spaCy
- **Frontend**: React or Next.js (optional)
- **Optional Enhancements**: GPT-4 for backup section detection, OCR for scanned syllabi

---

## 🚀 Status

🧱 In development — currently building:
- TA/contact info extraction
- Grading weight parser
- Summary output format

---

## 🛠️ Local Setup

```bash
# Backend
cd backend
pip install -r requirements.txt
python parser.py

# (Optional) Frontend
cd frontend
npm install
npm run dev
