# 🚀 AI-Powered LinkedIn Content Automation

An end-to-end workflow automation built using **n8n** to streamline LinkedIn content creation from PDF documents. The workflow eliminates the manual process of reading PDF documents, extracting relevant information, generating AI-powered content, and preparing it for publishing.

This project was developed during my internship at **Konfluence Infotech LLP** to automate an internal content creation workflow.

---

## 📌 Problem Statement

The existing workflow required team members to:

- 📄 Open PDF documents manually
- 📖 Read and identify important content
- ✍️ Write LinkedIn posts manually
- 📋 Copy content into LinkedIn
- 🚀 Publish the post

This repetitive process was time-consuming and reduced productivity.

---

## 💡 Solution

This workflow automates the majority of the content creation pipeline.

The automation:

- 📥 Reads PDF links from Google Sheets
- 📄 Downloads PDF documents automatically
- 🔍 Extracts textual content
- 🤖 Uses Google Gemini AI to generate content
- ✨ Formats the generated output
- 📊 Updates Google Sheets automatically
- ✅ Tracks processing status
- 🔗 Includes a LinkedIn publishing node for complete workflow automation*

---

## ✨ Features

- 📄 Automated PDF processing
- 📊 Google Sheets integration
- 🤖 AI-powered content generation
- 📝 Prompt-driven workflow
- ✅ Automatic status tracking
- 🚫 Duplicate processing prevention
- 🧩 Modular workflow architecture
- ⚙️ Enterprise-ready automation design

---

## 🔄 Workflow

```text
Google Sheets
        │
        ▼
Read PDF Link
        │
        ▼
Download PDF
        │
        ▼
Extract Text
        │
        ▼
Generate Content using Gemini AI
        │
        ▼
Format Output
        │
        ▼
Update Google Sheets
        │
        ▼
Update Processing Status
        │
        ▼
LinkedIn Publishing (Work in Progress)
```

---

## 🛠️ Tech Stack

- n8n
- Google Gemini API
- Google Sheets API
- HTTP Request
- PDF Processing
- REST APIs
- Workflow Automation

---

## 📂 Project Structure

```text
.
├── LinkedIn Post Automation.json
├── README.md
└── .gitignore
```

---

## ⚙️ Prerequisites

Before running the workflow, configure the following credentials in n8n:

- Google Sheets
- Google Gemini API

🔒 The workflow uses n8n's encrypted credential management system. No API keys are stored in this repository.

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/ai-linkedin-content-automation.git
```

### Import the Workflow

- Open your n8n instance.
- Import `LinkedIn Post Automation.json`.
- Configure the required credentials.
- Execute the workflow.

---

## 📈 Current Status

### ✅ Completed

- Google Sheets Integration
- PDF Download
- PDF Text Extraction
- AI-powered Content Generation
- JSON Parsing
- Automated Formatting
- Status Tracking
- Google Sheets Updates

### 🚧 In Progress

- LinkedIn Post Publishing

> **Note:** The LinkedIn publishing node is included in the workflow architecture but is currently not functional due to LinkedIn API access limitations. The generated content is successfully prepared and stored, making it ready for manual or future automated publishing.

---

## 🔮 Future Improvements

- 🔗 Functional LinkedIn API integration
- 🖼️ AI-generated images
- 🌐 Multi-platform publishing
- 📅 Content scheduling
- 📊 Analytics dashboard
- 📧 Email notifications

---

## 🎯 Skills Demonstrated

- Workflow Automation
- Generative AI Integration
- API Integration
- Prompt Engineering
- PDF Processing
- Google Workspace Automation
- JSON Processing
- Business Process Automation
- Enterprise Workflow Design

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository, open an issue, or submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Niranjan Borse**

🔗 LinkedIn: https://linkedin.com/in/niranjan-borse-8449a924a

💻 GitHub: https://github.com/NiranjanBorse1