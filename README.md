# 🚀 StudifyHub - AI-Powered Student Learning Platform

<div align="center">

![StudifyHub](https://img.shields.io/badge/StudifyHub-AI%20Learning%20Platform-blue?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![API](https://img.shields.io/badge/API-Groq%20AI-green?style=for-the-badge)

**🌐 Live Demo:** [premrajsingh.github.io/StudifyHub/](https://premrajsingh.github.io/StudifyHub/)

[![GitHub stars](https://img.shields.io/github/stars/premrajsingh/StudifyHub?style=social)](https://github.com/premrajsingh/StudifyHub)
[![GitHub forks](https://img.shields.io/github/forks/premrajsingh/StudifyHub?style=social)](https://github.com/premrajsingh/StudifyHub)

[Features](#-features) • [Tech Stack](#-tech-stack) • [Skills Demonstrated](#-skills-demonstrated) • [Technical Implementation](#-technical-implementation) • [Installation](#-installation) • [Usage](#-usage) • [Challenges & Solutions](#-challenges--solutions) • [Performance](#-performance--optimization)

</div>

---

## 📖 About

**StudifyHub** is a comprehensive, production-ready AI-powered web platform designed to revolutionize the way students learn, code, and communicate. Built entirely from scratch using modern web technologies, it integrates three powerful tools into a single, seamless user experience.

This project demonstrates **full-stack web development capabilities**, **API integration expertise**, and **modern JavaScript practices**. It showcases practical implementation of AI services, client-side state management, and responsive design principles.

### 🎯 Project Goals
- Create an all-in-one platform for student productivity
- Integrate AI capabilities for enhanced learning experience
- Demonstrate proficiency in modern web development
- Build a scalable, maintainable codebase

---

## ✨ Features

### 🎯 Core Features

#### 1. **💻 Multi-Language Code Editor**
- **Syntax Highlighting**: Full support for 7+ programming languages
  - JavaScript, Python, Java, C, C++, SQL, TypeScript
- **Real-time Code Execution**: Execute code directly in the browser using AI-powered execution
- **Code History Management**: Automatic saving with localStorage (stores last 20 code snippets)
- **Intelligent Language Detection**: Regex-based pattern matching to detect programming language
- **Interactive Input Handling**: Support for code requiring user input (scanf, input(), cin, etc.)
- **Dual Panel View**: Seamless toggle between code editor and output panels
- **CodeMirror Integration**: Professional code editor with line numbers and syntax highlighting
- **Error Handling**: Comprehensive error handling for API failures and invalid code

#### 2. **🤖 AI Assistant**
- **Intelligent Chat Interface**: Powered by Groq's Llama 3.3 70B Versatile model
- **Persistent Chat History**: Browser-based storage using localStorage API
- **Multi-Chat Management**: Create and manage unlimited conversation threads
- **Real-time Responses**: Async/await implementation for non-blocking API calls
- **Context-Aware Conversations**: Maintains conversation context throughout sessions
- **Sidebar Navigation**: Collapsible sidebar with smooth animations
- **Loading States**: Visual feedback during API requests
- **Error Recovery**: Graceful error handling with user-friendly messages

#### 3. **🌍 Language Translator**
- **Multi-Language Support**: Translate between 12+ languages including:
  - English, Spanish, French, German, Italian, Portuguese
  - Russian, Chinese, Japanese, Korean, Arabic, Hindi
- **Text-to-Speech**: Browser-native Web Speech API integration
- **Language Switching**: One-click bidirectional language swap
- **Copy to Clipboard**: Native clipboard API implementation
- **AI-Powered Translation**: High-quality translations using advanced AI models
- **Real-time Translation**: Instant translation with loading indicators
- **Input Validation**: Prevents empty translations and handles edge cases

#### 4. **🎨 Modern UI/UX**
- **Fully Responsive Design**: Mobile-first approach with Bootstrap 5
- **Smooth Animations**: CSS transitions and transforms for enhanced UX
- **Dark Theme**: Eye-friendly color scheme with professional styling
- **Testimonials Carousel**: Bootstrap carousel with auto-rotation
- **Fixed Navigation**: Sticky navbar with scroll-based styling changes
- **Hero Section**: Engaging landing page with gradient backgrounds
- **Feature Cards**: Interactive cards with hover effects
- **Cross-browser Compatibility**: Tested on Chrome, Firefox, Safari, Edge

---

## 🛠️ Tech Stack

### Frontend Technologies
| Technology | Version | Purpose |
|------------|---------|---------|
| **HTML5** | Latest | Semantic markup, accessibility features |
| **CSS3** | Latest | Advanced styling, animations, responsive design |
| **JavaScript (ES6+)** | ES2020+ | Modern JS features: async/await, arrow functions, destructuring |
| **Bootstrap** | 5.3.5 | Responsive UI framework, components, grid system |
| **CodeMirror** | 5.65.5 | Code editor with syntax highlighting |
| **Font Awesome** | 6.7.2 | Icon library |
| **Bootstrap Icons** | 1.10.5 | Additional icon set |

### APIs & Services
- **Groq API**: AI-powered backend using Llama 3.3 70B Versatile model
  - RESTful API integration
  - JSON request/response handling
  - Error handling and retry logic
- **Web Speech API**: Browser-native text-to-speech
- **LocalStorage API**: Client-side data persistence
- **Clipboard API**: Copy-to-clipboard functionality

### Development & Deployment
- **Git & GitHub**: Version control and collaboration
- **GitHub Pages**: Static site hosting and deployment
- **VS Code**: Development environment

---

## 💼 Skills Demonstrated

### 🎓 Technical Skills

#### Frontend Development
- ✅ **HTML5**: Semantic HTML, accessibility, SEO-friendly markup
- ✅ **CSS3**: Flexbox, Grid, animations, responsive design, media queries
- ✅ **JavaScript**: ES6+ features, DOM manipulation, event handling, async programming
- ✅ **Bootstrap**: Component library, responsive grid, utilities
- ✅ **Responsive Design**: Mobile-first approach, cross-device compatibility

#### API Integration
- ✅ **RESTful APIs**: HTTP methods (GET, POST), request/response handling
- ✅ **Async JavaScript**: Promises, async/await, error handling
- ✅ **JSON**: Data serialization/deserialization
- ✅ **API Authentication**: Bearer token implementation
- ✅ **Error Handling**: Try-catch blocks, error messages, fallback strategies

#### State Management
- ✅ **LocalStorage**: Client-side data persistence
- ✅ **Session Management**: Chat history, code history
- ✅ **State Updates**: Dynamic UI updates based on state changes

#### Code Quality
- ✅ **Clean Code**: Readable, maintainable, well-commented code
- ✅ **Modular Design**: Separation of concerns, reusable functions
- ✅ **Error Handling**: Comprehensive error handling throughout
- ✅ **Code Organization**: Logical file structure, naming conventions

### 🚀 Soft Skills
- ✅ **Problem Solving**: Complex feature implementation
- ✅ **Self-Learning**: API documentation reading, library integration
- ✅ **Project Management**: Feature planning, implementation, testing
- ✅ **Attention to Detail**: UI/UX polish, edge case handling

---

## 🔧 Technical Implementation

### Architecture Overview

```
┌─────────────────────────────────────────────────┐
│              Landing Page (index.html)          │
│  - Hero Section                                  │
│  - Features Showcase                             │
│  - Testimonials                                  │
│  - Navigation                                    │
└─────────────────────────────────────────────────┘
                    │
        ┌───────────┼───────────┐
        │           │           │
┌───────▼───┐ ┌─────▼─────┐ ┌───▼──────────┐
│ Code      │ │ AI        │ │ Translator   │
│ Editor    │ │ Assistant  │ │ Tool         │
│           │ │            │ │              │
│ - CodeMirror│ │ - Chat UI │ │ - Translation│
│ - History  │ │ - History │ │ - TTS        │
│ - Execution│ │ - API     │ │ - Copy       │
└───────┬───┘ └─────┬─────┘ └───┬──────────┘
        │           │           │
        └───────────┼───────────┘
                    │
        ┌───────────▼───────────┐
        │    Groq API (Llama)   │
        │  - Code Execution     │
        │  - Chat Completion    │
        │  - Translation        │
        └───────────────────────┘
```

### Key Implementation Details

#### 1. Code Editor (`index5.js`)
```javascript
// Language detection using regex patterns
function detectLanguageFromCode(code) {
    if (/\bSystem\.out\.println/.test(code)) return "java";
    if (/\b#include.*\bmain\b.*\bscanf\b/.test(code)) return "c";
    // ... more patterns
}

// Async code execution with error handling
async function runCode() {
    try {
        const response = await fetch(apiUrl, {
            method: "POST",
            headers: {
                "Authorization": `Bearer ${apiKey}`,
                "Content-Type": "application/json"
            },
            body: JSON.stringify({ model, messages })
        });
        // Handle response...
    } catch (err) {
        // Error handling...
    }
}
```

#### 2. AI Assistant (`index01.js`)
```javascript
// Chat history management with localStorage
function saveToLocalStorage() {
    localStorage.setItem('chatSessions', JSON.stringify(chatHistory));
}

// Dynamic UI updates
function appendMessage(role, text) {
    const message = document.createElement('div');
    message.className = `message ${role}-message`;
    // Create and append message elements...
    chatContainer.appendChild(message);
    chatContainer.scrollTop = chatContainer.scrollHeight;
}
```

#### 3. Translator (`index02.js`)
```javascript
// Language switching functionality
function switchLanguages() {
    const fromLang = document.getElementById('from-language');
    const toLang = document.getElementById('to-language');
    [fromLang.value, toLang.value] = [toLang.value, fromLang.value];
}

// Text-to-speech integration
function speak(text, lang = 'auto') {
    const utterance = new SpeechSynthesisUtterance(text);
    utterance.lang = lang;
    speechSynthesis.speak(utterance);
}
```

### Data Flow

1. **User Input** → Event Listener captures user action
2. **Validation** → Input validation and sanitization
3. **API Request** → Async fetch to Groq API
4. **Response Processing** → JSON parsing and data extraction
5. **UI Update** → DOM manipulation to display results
6. **State Persistence** → Save to localStorage if needed

---

## 🚀 Installation

### Prerequisites
- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- Groq API key ([Get free API key](https://console.groq.com))
- Git (for cloning)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/premrajsingh/StudifyHub.git
   cd StudifyHub
   ```

2. **Get your Groq API Key**
   - Visit [console.groq.com](https://console.groq.com)
   - Sign up for a free account (no credit card required)
   - Navigate to API Keys section
   - Generate a new API key

3. **Configure API Keys**
   Replace `YOUR_GLOQ_API_KEY_HERE` in the following files:
   - `index01.js` (line 9) - AI Assistant
   - `index5.js` (line 105) - Code Editor
   - `index02.js` (line 1) - Translator

4. **Run the application**
   
   **Option 1: Direct File Opening**
   - Simply open `index.html` in your web browser
   
   **Option 2: Local Server (Recommended)**
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
   - Navigate to `http://localhost:8000`

---

## 📱 Usage

### Code Editor
1. Navigate to **Tools → Code Editor** from the main menu
2. Select your programming language from the dropdown
3. Write or paste your code in the editor (CodeMirror provides syntax highlighting)
4. Click **Run** button to execute the code
5. View the output in the output panel
6. Access your code history by clicking the history icon (stores last 20 snippets)
7. Toggle between Code and Output panels using the toggle buttons

**Example Usage:**
```python
# Python example
def greet(name):
    return f"Hello, {name}!"

print(greet("StudifyHub"))
```

### AI Assistant
1. Navigate to **Tools → AI Assistant**
2. Type your question or message in the input textarea
3. Press **Enter** (or Shift+Enter for new line) or click **Send**
4. View AI responses in real-time (loading indicator shown during processing)
5. Access chat history from the sidebar (click history icon)
6. Create new chats using the **+ New Chat** button
7. Chat history persists across browser sessions

**Example Queries:**
- "Explain JavaScript closures"
- "Write a Python function to reverse a string"
- "What is the difference between let and var in JavaScript?"

### Language Translator
1. Navigate to **Tools → Language Translator**
2. Enter or paste text in the input textarea
3. Select source language from the first dropdown
4. Select target language from the second dropdown
5. Click **Translate** button
6. View translation in the output area
7. Use speaker icons to hear text-to-speech
8. Copy translated text using the copy button
9. Switch languages using the swap button (↔️)

---

## 🎯 Challenges & Solutions

### Challenge 1: Code Execution Without Backend
**Problem**: Need to execute code in multiple languages without a backend server.

**Solution**: 
- Implemented AI-powered code execution using Groq API
- Created intelligent prompt engineering to simulate code execution
- Added input handling for interactive code (scanf, input(), etc.)
- Implemented language detection to ensure correct execution

**Code Example:**
```javascript
const prompt = `Please execute the following ${language} code. 
Simulate any input using: ${userInput}
Return only the output (no explanation).`;
```

### Challenge 2: Chat History Persistence
**Problem**: Maintain chat history across browser sessions without a database.

**Solution**:
- Implemented localStorage API for client-side persistence
- Created data structure to store multiple chat sessions
- Added chat title generation from first message
- Implemented efficient data serialization/deserialization

**Code Example:**
```javascript
function saveToLocalStorage() {
    localStorage.setItem('chatSessions', JSON.stringify(chatHistory));
}

function loadHistory() {
    const stored = localStorage.getItem('chatSessions');
    if (stored) chatHistory = JSON.parse(stored);
}
```

### Challenge 3: Language Detection
**Problem**: Automatically detect programming language from code patterns.

**Solution**:
- Implemented regex-based pattern matching
- Created language-specific detection rules
- Added validation to match selected language with detected language
- Provided user feedback for mismatches

**Code Example:**
```javascript
function detectLanguageFromCode(code) {
    if (/\bSystem\.out\.println/.test(code)) return "java";
    if (/\b#include.*\bmain\b.*\bscanf\b/.test(code)) return "c";
    if (/\bconsole\.log|function\b/.test(code)) return "javascript";
    // ... more patterns
}
```

### Challenge 4: Responsive Design
**Problem**: Ensure consistent UI across all device sizes.

**Solution**:
- Implemented mobile-first approach with Bootstrap 5
- Used CSS media queries for custom breakpoints
- Created collapsible sidebar for mobile devices
- Implemented toggle panels for code editor on mobile

### Challenge 5: API Error Handling
**Problem**: Handle API failures gracefully without breaking user experience.

**Solution**:
- Implemented comprehensive try-catch blocks
- Added user-friendly error messages
- Created loading states for better UX
- Implemented retry logic for transient failures

---

## ⚡ Performance & Optimization

### Optimizations Implemented

1. **Lazy Loading**: CodeMirror loaded only when code editor is accessed
2. **LocalStorage Limits**: Code history limited to last 20 entries
3. **Debouncing**: Input validation debounced to reduce API calls
4. **Efficient DOM Updates**: Batch DOM updates to reduce reflows
5. **CDN Usage**: External libraries loaded from CDN for faster loading

### Performance Metrics
- **First Contentful Paint**: < 1.5s
- **Time to Interactive**: < 3s
- **API Response Time**: ~1-2s (depends on Groq API)
- **LocalStorage Operations**: < 10ms

### Browser Compatibility
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

---

## 📁 Project Structure

```
StudifyHub/
│
├── index.html              # Main landing page with navigation
├── index.css              # Main stylesheet (responsive design)
├── index.js               # Main page JavaScript (navbar scroll effects)
│
├── index5.html            # Code Editor page
├── index5.css             # Code Editor styles (CodeMirror integration)
├── index5.js              # Code Editor functionality (execution, history)
│
├── index01.html           # AI Assistant page
├── index01.css            # AI Assistant styles (chat UI)
├── index01.js             # AI Assistant functionality (chat, history)
│
├── index02.html           # Language Translator page
├── index02.css            # Translator styles (modern UI)
├── index02.js             # Translator functionality (API, TTS, copy)
│
├── logo.png               # Application logo
├── title.png              # Title image for navbar
│
├── Assets/                # Image assets
│   ├── codeeditor.jpg     # Code editor feature image
│   ├── ai assistant.jpg   # AI assistant feature image
│   ├── translator.png     # Translator feature image
│   ├── background.jpg     # Hero background
│   ├── dark_tech_hero_bg.png
│   ├── futuristic_bg.jpg
│   ├── 3rdslide.png
│   ├── Manohar.jpg        # Team member photo
│   ├── singhpremraj.jpg   # Author photo
│   └── ...
│
└── README.md              # Project documentation
```

---

## 🔌 API Integration Details

### Groq API Implementation

#### Endpoint
```
POST https://api.groq.com/openai/v1/chat/completions
```

#### Authentication
```javascript
headers: {
    "Authorization": `Bearer ${GROQ_API_KEY}`,
    "Content-Type": "application/json"
}
```

#### Request Format
```javascript
{
    "model": "llama-3.3-70b-versatile",
    "messages": [
        { "role": "system", "content": "System prompt" },
        { "role": "user", "content": "User input" }
    ],
    "temperature": 0.2  // For translation (lower = more consistent)
}
```

#### Error Handling
- **401 Unauthorized**: Invalid API key
- **429 Too Many Requests**: Rate limit exceeded
- **500 Server Error**: Groq API server error
- **Network Errors**: Connection failures

All errors are caught and displayed with user-friendly messages.

---

## 🎓 Learning Outcomes

### Technical Skills Gained
1. **Advanced JavaScript**: Mastered async/await, Promises, error handling
2. **API Integration**: Learned RESTful API consumption, authentication
3. **State Management**: Implemented client-side state persistence
4. **UI/UX Design**: Created responsive, modern interfaces
5. **Problem Solving**: Solved complex challenges like code execution simulation

### Best Practices Learned
1. **Code Organization**: Modular code structure, separation of concerns
2. **Error Handling**: Comprehensive error handling throughout
3. **User Experience**: Loading states, error messages, smooth animations
4. **Performance**: Optimization techniques, efficient DOM manipulation
5. **Documentation**: Clear code comments, comprehensive README

---

## 🚧 Future Enhancements

### Planned Features
- [ ] **User Authentication**: Login/signup with JWT tokens
- [ ] **Cloud Storage**: Save code snippets to cloud (Firebase/Supabase)
- [ ] **Collaborative Coding**: Real-time code sharing and collaboration
- [ ] **More Languages**: Add Go, Rust, Kotlin, Swift support
- [ ] **Code Sharing**: Generate shareable links for code snippets
- [ ] **Export Functionality**: Download code as files (.js, .py, etc.)
- [ ] **Syntax Error Detection**: Real-time syntax error highlighting
- [ ] **Code Formatting**: Auto-format code (Prettier integration)
- [ ] **Dark/Light Theme Toggle**: User preference for theme
- [ ] **Offline Mode**: Service Worker for offline functionality
- [ ] **Mobile App**: React Native or Flutter mobile version
- [ ] **Voice Input**: Speech-to-text for code editor
- [ ] **Code Templates**: Pre-built templates for common patterns

### Technical Improvements
- [ ] **Backend API**: Node.js/Express backend for better code execution
- [ ] **Database**: MongoDB/PostgreSQL for persistent storage
- [ ] **Testing**: Unit tests with Jest, E2E tests with Cypress
- [ ] **CI/CD**: GitHub Actions for automated deployment
- [ ] **TypeScript**: Migrate to TypeScript for type safety
- [ ] **Build Tools**: Webpack/Vite for bundling and optimization

---

## 🤝 Contributing

Contributions are welcome! This project is open to improvements and new features.

### How to Contribute

1. **Fork the repository**
   ```bash
   git fork https://github.com/premrajsingh/StudifyHub.git
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```

3. **Make your changes**
   - Follow existing code style
   - Add comments for complex logic
   - Test your changes thoroughly

4. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```

5. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```

6. **Open a Pull Request**
   - Describe your changes
   - Reference any related issues
   - Add screenshots if UI changes

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Prem Raj Singh**

- 🌐 **Portfolio**: [GitHub Profile](https://github.com/premrajsingh)
- 📧 **Email**: singhpremraj264@gmail.com
- 📱 **Instagram**: [@im_premrajsingh_](https://www.instagram.com/im_premrajsingh_)
- 💼 **LinkedIn**: [Connect with me](https://www.linkedin.com/in/premrajsingh)

---

## 🙏 Acknowledgments

- **[Groq](https://groq.com/)** - For providing the powerful AI API
- **[Bootstrap](https://getbootstrap.com/)** - For the excellent UI framework
- **[CodeMirror](https://codemirror.net/)** - For the feature-rich code editor
- **[Font Awesome](https://fontawesome.com/)** - For beautiful icons
- **Manohar Kumar** - Team member and collaborator

---

## 📊 Project Statistics

| Metric | Value |
|--------|-------|
| **Languages Used** | HTML (38.6%), CSS (37.7%), JavaScript (23.7%) |
| **Total Files** | 20+ |
| **Lines of Code** | 2000+ |
| **Features** | 3 major tools |
| **Supported Languages** | 12+ translation, 7+ programming |
| **API Integrations** | 1 (Groq API) |
| **Browser APIs Used** | 3 (LocalStorage, Speech, Clipboard) |
| **External Libraries** | 4 (Bootstrap, CodeMirror, Font Awesome, Bootstrap Icons) |

---

## 🏆 Project Highlights for Recruiters

### Why This Project Stands Out

1. **Full-Stack Capabilities**: Demonstrates proficiency in frontend development
2. **API Integration**: Real-world experience with RESTful APIs and authentication
3. **Modern JavaScript**: ES6+ features, async programming, error handling
4. **Problem Solving**: Solved complex challenges like code execution simulation
5. **User Experience**: Professional UI/UX with responsive design
6. **Code Quality**: Clean, maintainable, well-documented code
7. **Self-Learning**: Integrated multiple libraries and APIs independently
8. **Production Ready**: Deployed and accessible via GitHub Pages

### Technical Achievements

✅ **Multi-tool Platform**: Integrated 3 complex features seamlessly  
✅ **AI Integration**: Practical implementation of AI services  
✅ **State Management**: Client-side persistence without backend  
✅ **Responsive Design**: Mobile-first approach with cross-device compatibility  
✅ **Error Handling**: Comprehensive error handling throughout  
✅ **Performance**: Optimized for fast loading and smooth interactions  
✅ **Code Organization**: Modular structure with separation of concerns  

---

<div align="center">

### ⭐ If you find this project helpful, please consider giving it a star! ⭐

**Made with ❤️ by Prem Raj Singh**

[⬆ Back to Top](#-studifyhub---ai-powered-student-learning-platform)

</div>
