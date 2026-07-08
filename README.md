# AI-Powered LinkedIn Content Automation

An intelligent workflow automation built with **n8n** that transforms PDF documents into professional, AI-generated LinkedIn-ready posts. The workflow automates document processing, text extraction, and content generation using Large Language Models (LLMs), reducing manual effort in creating engaging social media content.

---

## Features

- 📄 Automated PDF text extraction
- 🤖 AI-powered LinkedIn post generation
- ✍️ Prompt-based content generation using LLMs
- 🔄 End-to-end workflow automation with n8n
- 📊 Google Sheets integration for workflow management
- ⚙️ Modular and extensible workflow design

---

## Workflow

```
PDF Input
      │
      ▼
Read PDF
      │
      ▼
Extract Text
      │
      ▼
Generate LinkedIn Post using AI
      │
      ▼
Store / Review Output
```

---

## Tech Stack

- n8n
- Google Gemini API
- Google Sheets
- PDF Processing
- REST APIs
- Workflow Automation

---

## Project Structure

```
linkedin-content-automation/
│
├── linkedin-automation.json
├── README.md
└── .gitignore
```

---

## Prerequisites

Before running the workflow, ensure you have:

- n8n installed (Cloud or Self-hosted)
- Google Gemini API credentials
- Google Sheets credentials
- A Google Spreadsheet for managing workflow data

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/linkedin-content-automation.git
```

### 2. Open n8n

Start your n8n instance.

### 3. Import the workflow

Import the exported workflow file:

```
linkedin-automation.json
```

### 4. Configure Credentials

Create the following credentials in n8n:

- Google Sheets
- Google Gemini API

The workflow references n8n credentials only. No API keys are stored in this repository.

### 5. Execute the Workflow

Run the workflow and provide the required input document.

---

## Configuration

This project uses **n8n Credentials** for authentication.

Required credentials include:

- Google Sheets Credentials
- Google Gemini API Credentials

Authentication is managed securely by n8n. Sensitive API keys and credentials are not included in this repository.

---

## Use Cases

- AI-assisted LinkedIn content creation
- Document-to-social media content generation
- Workflow automation
- Personal branding
- Content marketing
- Enterprise content automation

---

## Future Improvements

- Automatic LinkedIn publishing
- Multi-platform social media support
- Content scheduling
- AI-generated image creation
- Advanced prompt customization
- Analytics and reporting dashboard

---

## Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to fork the repository, open issues, or submit pull requests.

---

## License

This project is licensed under the MIT License.

---

## Author

**Niranjan Borse**

LinkedIn: https://linkedin.com/in/niranjan-borse-8449a924a

GitHub: https://github.com/NiranjanBorse1
