# 🚀 StudifyHub - AI-Powered Student Learning Platform

<div align="center">

![StudifyHub](https://img.shields.io/badge/StudifyHub-AI%20Learning%20Platform-blue?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Live Demo:** [premrajsingh.github.io/StudifyHub/](https://premrajsingh.github.io/StudifyHub/)

[Features](#-features) • [Tech Stack](#-tech-stack) • [Installation](#-installation) • [Usage](#-usage) • [Project Structure](#-project-structure) • [API Integration](#-api-integration) • [Contributing](#-contributing)

</div>

---

## 📖 About

**StudifyHub** is a comprehensive, AI-powered web platform designed to revolutionize the way students learn, code, and communicate. Built with modern web technologies, it integrates multiple powerful tools into a single, user-friendly interface that makes studying smarter, faster, and more efficient.

Whether you're a student taking notes, a developer writing code, or someone learning a new language, StudifyHub provides all the essential tools you need in one place. The platform leverages cutting-edge AI technology (Groq's Llama 3.3 70B model) to deliver intelligent assistance across all features.

---

## ✨ Features

### 🎯 Core Features

#### 1. **💻 Multi-Language Code Editor**
- **Syntax Highlighting**: Full support for 7+ programming languages
  - JavaScript, Python, Java, C, C++, SQL, TypeScript
- **Real-time Code Execution**: Execute code directly in the browser using AI-powered execution
- **Code History**: Automatic saving of code snippets with timestamp tracking
- **Language Detection**: Intelligent detection of programming language from code patterns
- **Input Handling**: Support for interactive code that requires user input
- **Dual Panel View**: Toggle between code editor and output panels seamlessly

#### 2. **🤖 AI Assistant**
- **Intelligent Chat Interface**: Powered by Groq's Llama 3.3 70B model
- **Conversation History**: Persistent chat sessions saved in browser storage
- **Multi-Chat Management**: Create and manage multiple conversation threads
- **Real-time Responses**: Instant AI-powered answers to any question
- **Context-Aware**: Maintains conversation context throughout the session
- **Sidebar Navigation**: Easy access to chat history with toggle functionality

#### 3. **🌍 Language Translator**
- **Multi-Language Support**: Translate between 12+ languages including:
  - English, Spanish, French, German, Italian, Portuguese
  - Russian, Chinese, Japanese, Korean, Arabic, Hindi
- **Text-to-Speech**: Listen to translations in both source and target languages
- **Language Switching**: One-click swap between source and target languages
- **Copy to Clipboard**: Quick copy functionality for translated text
- **AI-Powered Translation**: High-quality translations using advanced AI models

#### 4. **🎨 Modern UI/UX**
- **Responsive Design**: Fully responsive layout that works on all devices
- **Bootstrap 5 Integration**: Modern, professional UI components
- **Smooth Animations**: Enhanced user experience with smooth transitions
- **Dark Theme**: Eye-friendly dark color scheme
- **Testimonials Section**: User reviews and feedback carousel
- **Professional Navigation**: Fixed navbar with smooth scroll effects

---

## 🛠️ Tech Stack

### Frontend Technologies
- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with animations and responsive design
- **JavaScript (ES6+)**: Modern JavaScript with async/await, localStorage API
- **Bootstrap 5.3.5**: Responsive UI framework
- **CodeMirror 5.65.5**: Feature-rich code editor component
- **Font Awesome 6.7.2**: Icon library
- **Bootstrap Icons**: Additional icon set

### APIs & Services
- **Groq API**: AI-powered backend using Llama 3.3 70B Versatile model
  - Code execution simulation
  - Natural language processing
  - Language translation
- **Web Speech API**: Text-to-speech functionality
- **LocalStorage API**: Client-side data persistence

### Development Tools
- **Git & GitHub**: Version control and deployment
- **GitHub Pages**: Hosting and deployment

---

## 🚀 Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A Groq API key (Get one free at [console.groq.com](https://console.groq.com))

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/premrajsingh/StudifyHub.git
   cd StudifyHub
   ```

2. **Get your Groq API Key**
   - Visit [console.groq.com](https://console.groq.com)
   - Sign up for a free account
   - Generate an API key

3. **Configure API Keys**
   - Open `index01.js` and replace `YOUR_GLOQ_API_KEY_HERE` with your API key
   - Open `index5.js` and replace `YOUR_GLOQ_API_KEY_HERE` with your API key
   - Open `index02.js` and replace `YOUR_GLOQ_API_KEY_HERE` with your API key

4. **Run the application**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx http-server
     ```
   - Navigate to `http://localhost:8000`

---

## 📱 Usage

### Code Editor
1. Navigate to **Tools → Code Editor** from the main menu
2. Select your programming language from the dropdown
3. Write or paste your code in the editor
4. Click **Run** to execute the code
5. View the output in the output panel
6. Access your code history by clicking the history icon

### AI Assistant
1. Navigate to **Tools → AI Assistant**
2. Type your question or message in the input area
3. Press **Enter** or click **Send**
4. View AI responses in real-time
5. Access chat history from the sidebar
6. Create new chats using the **+ New Chat** button

### Language Translator
1. Navigate to **Tools → Language Translator**
2. Enter or paste text in the input area
3. Select source and target languages
4. Click **Translate** to get the translation
5. Use the speaker icon to hear the text
6. Copy translated text using the copy button
7. Switch languages using the swap button

---

## 📁 Project Structure

```
StudifyHub/
│
├── index.html              # Main landing page
├── index.css              # Main stylesheet
├── index.js               # Main page JavaScript
│
├── index5.html            # Code Editor page
├── index5.css             # Code Editor styles
├── index5.js              # Code Editor functionality
│
├── index01.html           # AI Assistant page
├── index01.css            # AI Assistant styles
├── index01.js             # AI Assistant functionality
│
├── index02.html           # Language Translator page
├── index02.css            # Translator styles
├── index02.js             # Translator functionality
│
├── logo.png               # Application logo
├── title.png              # Title image
│
├── Images/
│   ├── codeeditor.jpg     # Code editor feature image
│   ├── ai assistant.jpg   # AI assistant feature image
│   ├── translator.png     # Translator feature image
│   ├── background.jpg     # Background image
│   ├── dark_tech_hero_bg.png
│   ├── futuristic_bg.jpg
│   └── ...
│
└── README.md              # Project documentation
```

---

## 🔌 API Integration

### Groq API Configuration

The project uses Groq's API for AI-powered features. Here's how it's integrated:

#### Code Execution
```javascript
// Uses Llama 3.3 70B to simulate code execution
POST https://api.groq.com/openai/v1/chat/completions
```

#### AI Chat
```javascript
// Conversational AI using Llama 3.3 70B
POST https://api.groq.com/openai/v1/chat/completions
```

#### Translation
```javascript
// AI-powered translation service
POST https://api.groq.com/openai/v1/chat/completions
```

### API Rate Limits
- Free tier: Generous limits for development and testing
- Production: Consider upgrading for higher usage

---

## 🎯 Key Highlights

### For Recruiters & Employers

✅ **Full-Stack Web Development**: Demonstrates proficiency in HTML, CSS, and JavaScript  
✅ **API Integration**: Experience with RESTful APIs and async JavaScript  
✅ **Modern UI/UX**: Professional, responsive design with Bootstrap  
✅ **AI/ML Integration**: Practical implementation of AI services  
✅ **Local Storage**: Client-side data persistence and state management  
✅ **Code Quality**: Clean, well-structured, and maintainable code  
✅ **Version Control**: Git/GitHub workflow and deployment  
✅ **Problem Solving**: Complex feature implementation (code execution, chat history, etc.)  

### Technical Achievements

- **Multi-tool Platform**: Integrated 3 major features in a single application
- **AI-Powered**: Leveraged advanced AI models for multiple use cases
- **Real-time Processing**: Implemented async operations and API calls
- **Data Persistence**: LocalStorage implementation for user data
- **Responsive Design**: Mobile-first approach with Bootstrap
- **Code Editor**: Integrated third-party library (CodeMirror) with custom functionality

---

## 🚧 Future Enhancements

- [ ] User authentication and profiles
- [ ] Cloud-based code storage
- [ ] Collaborative coding features
- [ ] Additional programming languages support
- [ ] Code sharing and export functionality
- [ ] Enhanced AI model options
- [ ] Mobile app version
- [ ] Offline mode support
- [ ] Code syntax error detection
- [ ] Real-time collaboration features

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute to StudifyHub:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Prem Raj Singh**

- GitHub: [@premrajsingh](https://github.com/premrajsingh)
- Instagram: [@im_premrajsingh_](https://www.instagram.com/im_premrajsingh_)
- Email: singhpremraj264@gmail.com

---

## 🙏 Acknowledgments

- [Groq](https://groq.com/) for providing the AI API
- [Bootstrap](https://getbootstrap.com/) for the UI framework
- [CodeMirror](https://codemirror.net/) for the code editor
- [Font Awesome](https://fontawesome.com/) for icons

---

## 📊 Project Statistics

- **Languages**: HTML (38.6%), CSS (37.7%), JavaScript (23.7%)
- **Total Files**: 20+
- **Features**: 3 major tools
- **Supported Languages**: 12+ translation languages, 7+ programming languages

---

<div align="center">

**⭐ If you find this project helpful, please consider giving it a star! ⭐**

Made with ❤️ by Prem Raj Singh

</div>
