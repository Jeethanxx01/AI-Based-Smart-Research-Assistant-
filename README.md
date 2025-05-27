# 🤖 AI-Based Smart Research Assistant

<div align="center">

[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)](https://spring.io/projects/spring-boot)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Gemini API](https://img.shields.io/badge/Gemini_API-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)

</div>

## 📝 Overview

An innovative browser extension that revolutionizes the way researchers, students, and professionals interact with online content. This AI-powered tool provides instant text summarization and efficient note management capabilities, making research and information gathering more productive than ever.

## 📂 Quick Navigation
- [View Project Images](Images/)

## ✨ Key Features

### 🎯 Smart Text Summarization
- **AI-Powered Analysis**: Utilizes advanced Gemini API for intelligent text processing
- **Instant Results**: Get concise summaries with a single click
- **Context-Aware**: Maintains key information while reducing text length

### 📚 Note Management System
- **Organized Storage**: Save and categorize your summaries efficiently
- **Quick Access**: Retrieve past summaries with ease
- **Cross-Platform**: Access your notes across different devices

### 🌐 Browser Integration
- **Seamless Experience**: Works directly within your browser
- **Cross-Browser Support**: Compatible with Chrome and Firefox
- **Lightweight Design**: Minimal impact on browser performance

## 🛠️ Technical Architecture

### Frontend
- **HTML5 & CSS3**: Modern, responsive design
- **JavaScript**: Dynamic user interface
- **Browser Extension API**: Native browser integration

### Backend
- **Spring Boot**: Robust server-side processing
- **RESTful API**: Clean, scalable architecture
- **Secure Authentication**: Protected user data

### AI Integration
- **Gemini API**: State-of-the-art text processing
- **Natural Language Processing**: Advanced text analysis
- **Machine Learning**: Continuous improvement in summarization quality

## 🚀 Getting Started

### Prerequisites
- Java 17 or higher
- Maven 3.6+
- Modern web browser (Chrome/Firefox)
- Gemini API credentials

### Installation

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

2. **Backend Setup**
```bash
cd backend
./mvnw spring-boot:run
```

3. **Configure API Key**
```properties
# application.properties
gemmi.api.key=YOUR_API_KEY
```

4. **Browser Extension Installation**
- **Chrome**: 
  - Visit `chrome://extensions/`
  - Enable Developer Mode
  - Click "Load Unpacked"
  - Select the `extension/` directory

- **Firefox**:
  - Visit `about:debugging`
  - Click "This Firefox"
  - Select "Load Temporary Add-on"
  - Choose `manifest.json`

## 📁 Project Structure
```
.
├── backend/                 # Spring Boot application
│   ├── src/
│   │   ├── main/
│   │   └── test/
│   └── pom.xml
├── extension/              # Browser extension
│   ├── manifest.json
│   ├── popup/
│   ├── content/
│   └── background/
└── docs/                   # Documentation
```

## 🔮 Roadmap

### Phase 1 (Current)
- [x] Basic text summarization
- [x] Note management system
- [x] Browser extension integration

### Phase 2 (In Progress)
- [ ] Cloud synchronization
- [ ] Multi-language support
- [ ] Advanced search capabilities

### Phase 3 (Planned)
- [ ] Collaborative features
- [ ] AI-powered insights
- [ ] Custom summarization rules

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.