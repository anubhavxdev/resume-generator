# 🧾 Resume Generator (YAML-Based)

This project is a clean, professional resume/CV generator powered by YAML + HTML + GitHub Actions. It automatically generates a PDF resume and an HTML view from a single `resume.yaml` file.

![Generated PDF Resume](https://github.com/anubhavxdev/resume-generator/blob/main/docs/cv.pdf)

---

## ✨ Features

- 📄 Edit once → export as **PDF** and **HTML**
- ⚙️ Built using **Makefile** and **GitHub Actions**
- 📦 Powered by clean HTML, CSS, and LaTeX styling
- 🚀 Auto-build resume on every commit

---

## 🧱 Folder Structure

```bash
resume-generator/
├── resume.yaml          # Your editable resume content
├── docs/
│   ├── cv.pdf           # Auto-generated PDF resume
│   └── index.html       # Auto-generated HTML resume
├── .github/
│   └── workflows/
│       └── compile.yml  # GitHub Actions PDF builder
├── Makefile             # Local build tool
└── README.md
```
## ✍️ Editing Your Resume
Edit your main content inside the resume.yaml file. You can change:

Name, contact info

Work experience

Education

Skills, projects, etc.

Once you push to main, GitHub will:

Compile the YAML into HTML

Convert HTML to PDF

Save everything in the docs/ folder

## 📄 Output Example
✅ Live HTML resume (index.html)

✅ Generated PDF resume (cv.pdf)

## 
