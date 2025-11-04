# 📄 Resume Upload UI – React + Filestack

This is a simple React app that demonstrates how to build a **resume upload UI** using [Filestack](https://www.filestack.com) for drag-and-drop or mobile resume uploads.  
It supports **PDF** and **DOCX** formats, validates file types, and displays upload success confirmation.

---

## ✨ Features

- Upload resumes (PDF or DOCX) via file picker
- Drag-and-drop or mobile upload support
- File type and size validation
- Upload progress bar with success message

---

## 🚀 Demo Use Case

This is based on the following case study:

> “A job board startup needs to collect candidates' resumes—usually in PDF or DOCX format. Instead of building a complex upload system, the dev team uses Filestack’s file upload UI to allow resume uploads via drag-and-drop or mobile. It validates file types, shows upload status, and makes the process seamless for job seekers.”

---

## 📁 File Structure

This repository provides only the essential files needed for the Filestack resume uploader component.

```
filestack-resume-uploader/
├── src/
│   ├── ResumeUpload.js     # 👉 Upload component
│   └── App.js              # App entry point
├── LICENSE
└── README.md
```

> ℹ️ Other folders like `public/`, `.gitignore`, `package.json`, and `node_modules/` will be created automatically when you initialize the app locally using:
>
> `npx create-react-app resume-uploader`

---

## 🧰 Prerequisites

- Node.js (v14 or later)
- npm or yarn
- A [Filestack API Key](https://www.filestack.com/signup-start/)

---

## 🛠️ Installation

### 1. Clone the repository
git clone https://github.com/fileschool/filestack-snippets.git

### 2. Navigate to the project directory
cd filestack-snippets/content/blogs/filestack-resume-uploader

### 3. Install dependencies
npm install

