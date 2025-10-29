# IntelliSurvey

**AI-powered multimodal survey platform built for the Chrome Built-in AI Challenge 2025**

---

## Overview

IntelliSurvey is a web-based AI-powered survey platform that enables users to create, host, and analyze surveys using text, voice, images, and uploaded files—powered by Chrome's built-in AI capabilities.

The platform is designed to make survey creation and analysis smarter, faster, and more inclusive, allowing both creators and respondents to interact naturally through typing, speaking, or uploading media.

---

## Key Features

| Feature | Description | AI/Tech Used |
|---------|-------------|--------------|
| **AI Survey Generator** | Automatically generates survey questions based on a given topic | Chrome Prompt API |
| **Voice Input** | Allows respondents to speak their answers instead of typing | Chrome SpeechRecognition API |
| **Image/File Upload** | Enables respondents to upload images or files, which are analyzed by AI for insights | Chrome Prompt API (multimodal) |
| **AI Insights Dashboard** | Automatically generates response summaries and key insights using built-in AI | Chrome Summarizer API |
| **Privacy-Friendly** | Uses Chrome's on-device AI models to minimize cloud data transfers | Local execution |

---

## Architecture

```
Frontend (React + Tailwind)
|
├── Chrome Built-in AI APIs
| ├── Prompt API → Generates survey questions, analyzes responses
| ├── Summarizer API → Produces key insights
| ├── SpeechRecognition → Handles voice input
|
└── Firebase / LocalStorage → Stores surveys & responses
```

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React + TailwindCSS |
| **AI Integration** | Chrome Built-in AI APIs |
| **Voice Input** | Web Speech API |
| **Data Storage** | Firebase / LocalStorage |
| **Hosting** | Vercel / Netlify |
| **Version Control** | Git + GitHub |

---

## Getting Started

### Prerequisites

- Chrome browser (latest version or Canary)
- Node.js and npm installed
- Chrome Built-in AI enabled in `chrome://flags` (if required)

### Installation

**1. Clone the Repository**

```bash
git clone https://github.com/YOUR_USERNAME/intellisurvey.git
cd intellisurvey
```

**2. Install Dependencies**

```bash
npm install
```

**3. Run the Development Server**

```bash
npm run dev
```

**4. Access the Application**

Open your browser and navigate to `http://localhost:5173`

---

## Chrome Built-in AI APIs Used

| API | Purpose |
|-----|---------|
| **Prompt API** | Generate and analyze text/image responses |
| **Summarizer API** | Summarize survey results and extract insights |
| **SpeechRecognition API** | Process voice input from users |

**Documentation:** [Chrome AI APIs Documentation](https://developer.chrome.com/docs/ai)

---

## Why IntelliSurvey?

Traditional survey tools such as Google Forms or Typeform are limited to static text input and require manual data review. IntelliSurvey transforms the survey experience by leveraging Chrome's built-in AI to:

- **Streamline survey creation** through automated question generation
- **Enable natural interaction** through voice and image inputs
- **Provide instant insights** with AI-generated summaries and analysis
- **Ensure privacy** by keeping user data local and minimizing cloud transfers

---

## Demo & Screenshots

A comprehensive demo video (2-3 minutes) and screenshots will be added following deployment.

---

## Contributing

IntelliSurvey welcomes contributions from the community. To contribute:

1. **Fork the repository** to your GitHub account
2. **Create a feature branch**
   ```bash
   git checkout -b feature-name
   ```
3. **Commit your changes** with descriptive messages
   ```bash
   git commit -m "Add feature: description"
   ```
4. **Push to your fork**
   ```bash
   git push origin feature-name
   ```
5. **Open a Pull Request** with a clear description of your changes

Once your PR is merged, you will be automatically listed as a contributor on GitHub.

---

## License

This project is licensed under the MIT License. You are free to use, modify, and build upon this software.

---

## Author

**Aditya Naskar**  
Lead Developer & Founder  
IntelliSurvey

Built for the Chrome Built-in AI Challenge 2025

---

## Acknowledgements

- Google Chrome team for providing the Built-in AI APIs
- OpenAI and Hugging Face for inspiration and guidance
- All contributors who have helped shape and improve IntelliSurvey

---

> *"AI should empower humans to understand other humans—IntelliSurvey makes that happen."*
