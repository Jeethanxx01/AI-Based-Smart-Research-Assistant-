# AI-Based-Research-Assistant

A powerful browser extension that lets you **summarize any selected text instantly** and manage notes efficiently. Built with **Spring Boot** and **Gemmi API** on the backend, and a simple **HTML, CSS, JavaScript** frontend.

---

## ✨ Features

- 🔍 **Smart Summarization**  
  Highlight any text and click "Summarize" to generate a concise, AI-powered summary using the Gemmi API.

- 🗒️ **Easy Note Management**  
  Save summaries into your personal notes for future reference. Ideal for researchers, students, and professionals.

- 🌐 **Browser Extension**  
  Designed as a lightweight browser extension for quick, on-the-go access.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Spring Boot  
- **AI Summarization**: Gemmi API

---

## 🚀 Getting Started

### Prerequisites

- Java 17+
- Maven
- A web browser (Chrome or Firefox)
- A Gemmi API Key

### Backend Setup (Spring Boot)

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo/backend
./mvnw spring-boot:run
npm run deploy
```
Make sure to add your Gemmi API key in application.properties:

properties
Copy
Edit
gemmi.api.key=YOUR_API_KEY

### Frontend Setup (Browser Extension)

- Navigate to the extension/ directory.

- Load the extension in your browser:

- Chrome: Go to chrome://extensions/, enable Developer Mode, click Load Unpacked, and select the extension/ folder.

- Firefox: Go to about:debugging, click This Firefox, then Load Temporary Add-on, and select manifest.json.


### Project Structure

```markdown
.
├── backend/                 # Spring Boot backend for summarization
│   └── src/
├── extension/               # Browser extension source
│   ├── manifest.json
│   ├── popup.html
│   ├── popup.js
│   └── style.css
└── README.md
```


## 🧪 Example Usage

Select any text on a webpage.

Click the extension icon → “Summarize”.

View the summary and optionally save it to your notes.

## 📌 Future Enhancements
Cloud sync for notes

Support for multiple languages

Tagging and search features for notes

## 📃 License
This project is licensed under the MIT License.

## 🙌 Contributions
Feel free to open issues or pull requests. Suggestions and feedback are welcome!