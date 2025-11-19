# Filestack E-Learning Demo (Upload + Storage + CDN Delivery)

This demo shows how an e-learning platform can:
- Upload lesson materials (PDF, video, images)
- Store them automatically using Filestack
- Deliver them instantly via Filestack CDN

## Features
✔ Upload lesson files  
✔ Automatic CDN delivery URLs  
✔ Student-friendly content viewer  
✔ Modern UI with simple styling  

## Project Structure

```
filestack-elearning-demo/
│
├── index.html            # Upload interface
├── lesson-viewer.html    # Student viewer
├── style.css             # UI styling
└── README.md             # Setup instructions
```

## Setup Instructions
1. Replace `YOUR_API_KEY` inside `index.html`
2. Open `index.html` in your browser
3. Upload a file
4. Click **Open in Student Viewer** to load it instantly via CDN

## CDN Delivery URL Format

`https://cdn.filestackcontent.com/<file_handle>`

## Technologies Used

- Filestack File Picker
- Filestack Storage
- Filestack CDN
- HTML, CSS, JavaScript
