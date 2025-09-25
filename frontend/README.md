# 🚀 AI Web Builder - Frontend

A modern React application that transforms natural language prompts into live, publishable web projects using AI. Create, edit, preview, and publish complete websites with just a few clicks!

## ✨ Features

### 🤖 **AI-Powered Code Generation**
- Generate complete web projects from natural language prompts
- Creates HTML, CSS, and JavaScript files automatically
- Uses Google Gemini AI for intelligent code generation
- Supports complex project requests with modern web technologies

### 🎨 **Modern UI/UX**
- **Glassmorphism Design**: Beautiful frosted glass effects
- **Animated Background**: Dynamic gradient animations
- **Responsive Layout**: Works perfectly on desktop and mobile
- **Dark Theme**: Professional dark interface with smooth transitions
- **Live Preview**: Real-time preview of generated projects

### 📝 **Advanced Code Editor**
- **Monaco Editor**: VS Code-like editing experience
- **Syntax Highlighting**: HTML, CSS, JavaScript support
- **File Tabs**: Switch between HTML, CSS, and JS files
- **Auto-completion**: IntelliSense and code suggestions
- **Error Detection**: Real-time syntax error highlighting

### 🌐 **One-Click Publishing**
- **Netlify Integration**: Deploy to real URLs instantly
- **GitHub Pages**: Deploy to your GitHub repositories
- **Vercel Hosting**: Modern serverless deployment
- **Live URLs**: Share your creations with HTTPS URLs
- **Publish History**: Track all your published projects

### 🔧 **Developer Features**
- **Real-time Preview**: See changes instantly
- **Download Projects**: Export as ZIP files
- **Copy to Clipboard**: Quick code sharing
- **Project Management**: History and organization tools

## 🛠️ Technologies Used

### **Frontend Framework**
- **React 19**: Latest React with concurrent features
- **React DOM 19**: Modern rendering engine
- **React Scripts 5.0**: Create React App build tools

### **Code Editor & Preview**
- **Monaco Editor 4.7**: VS Code editor component
- **JSZip 3.10**: File compression and download
- **File-saver 2.0**: Browser file download utility

### **API & Communication**
- **Axios 1.10**: HTTP client for API calls
- **Proxy Configuration**: Seamless backend communication

### **Testing & Quality**
- **Testing Library**: React testing utilities
- **Jest DOM**: DOM testing utilities
- **Web Vitals**: Performance monitoring

## 📁 Project Structure

```
frontend/
├── public/
│   ├── index.html              # Main HTML template
│   ├── favicon.ico             # App icon
│   └── manifest.json           # PWA configuration
├── src/
│   ├── components/
│   │   ├── Header.js           # Top navigation and actions
│   │   ├── PromptPanel.js      # AI prompt input and file navigation
│   │   ├── CodeEditor.js       # Monaco code editor with tabs
│   │   ├── PreviewPanel.js     # Live preview with responsive frames
│   │   ├── PublishPanel.js     # Publishing interface and history
│   │   └── PublishSetup.js     # API key configuration modal
│   ├── hooks/
│   │   ├── useFileManager.js   # File state management
│   │   └── useAIGenerator.js   # AI generation logic
│   ├── utils/
│   │   ├── publishUtils.js     # Publishing service integration
│   │   └── fileUtils.js        # File manipulation utilities
│   ├── App.js                  # Main application component
│   ├── App.css                 # Global styles and animations
│   ├── index.js                # React application entry point
│   └── index.css               # Base CSS styles
├── .env                        # Environment variables (API keys)
├── .env.example                # Environment template
├── package.json                # Dependencies and scripts
└── README.md                   # This file
```

m
