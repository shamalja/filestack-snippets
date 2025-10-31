# 🛍️ Marketplace Product Image Upload (React + Filestack)

This project is a simple, accessible **product image uploader** component built in **React** using the [Filestack File Picker SDK](https://www.filestack.com/docs/uploads/pickers/). It's designed for marketplace sellers to easily upload product images from multiple sources.

---

## ✅ Features

- 📁 Upload up to **5 product images**
- 🖼️ Supports **image formats only** (`JPG`, `PNG`, `GIF`)
- ☁️ Upload from **Google Drive, Dropbox, Instagram, Facebook**, and more
- 🧠 Real-time file validation and error handling
- ✅ Upload feedback: success and error messages
- ♿ Accessibility features built-in

---

## 📂 File Structure

```
/src
├── ProductImageUploader.jsx   → Main React component
└── App.jsx                    → Renders the uploader
README.md                      → Project documentation
LICENSE                        → MIT License
```

---

## 🚀 Getting Started

### 1. Clone the repo

`git clone https://github.com/fileschool/filestack-snippets.git`

`cd filestack-snippets/content/blogs/marketplace-product-upload`

### 2. Install dependencies

`npm install`

### 3. Add your Filestack API key

In `ProductImageUploader.jsx`, replace this line:

`const client = filestack.init('YOUR_API_KEY');`

You can get a free API key from [Filestack](https://www.filestack.com/)

### 4. Start the dev server

`npm run dev`

Open your browser at `http://localhost:5173`

## 💡 Usage

This uploader is perfect for marketplace sellers during the product listing process. It provides an intuitive way to pick and preview images before submission, with zero need for technical knowledge.

---

## 📦 Dependencies
- [React](https://react.dev/)
- [Vite](https://vite.dev/)
- [Filestack JS SDK](https://www.filestack.com/sdks/javascript/)

---

## 📝 License

MIT License. See LICENSE for details.

---

## 🙌 Credits

This example was created for the tutorial:  
**[File Upload UI for Non-Technical Users](https://blog.filestack.com/file-upload-ui-for-non-technical-users/)**

**Powered by [Filestack](https://www.filestack.com/)**  
Created by **[Shamal Jayawardhana](https://www.linkedin.com/in/shamal-jayawardhana/)**

