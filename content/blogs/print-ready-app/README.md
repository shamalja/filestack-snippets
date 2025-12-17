# Print-Ready Image Workflow with Filestack

This example demonstrates how to build a simple web application that converts user-uploaded images into print-ready files using Filestack Workflows.

The example shows how to:

- Upload images using the Filestack File Picker

- Create a print-prep workflow with Filestack Workflows

- Run a print-prep workflow automatically

- Normalize color space and format for printing

- Retrieve and display the processed, print-ready image from Filestack’s CDN

This project is designed to support printing applications that need consistent, predictable input from user uploads.

---

## What This Demo Does

1. A user uploads an image using the Filestack File Picker

2. The uploaded file is sent to a Filestack Workflow

3. The workflow:

   - Inspects file metadata

   - Converts the image to CMYK

   - Normalizes format and quality
     
   - Resize the image

   - Stores the processed output

4. The app polls the workflow status

5. The final, print-ready image is displayed using Filestack’s CDN

---

## Project Structure

```
.
├── index.html     # UI for uploading and previewing images
├── style.css      # Basic styling
├── app.js         # Frontend logic (File Picker + workflow polling)
├── server.js      # Backend server (policy, signature, workflow API)
└── README.md
```

---

## Prerequisites

- Node.js v18 or later

- A Filestack account

- A Filestack Workflow configured in the dashboard

## Setup Instructions

### 1️⃣ Clone the repository

`git clone <your-repo-url>`

`cd print-ready-workflow-demo`


