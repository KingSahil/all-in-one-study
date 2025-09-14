# 📚 All-in-One Study Platform

A comprehensive, modern study application that combines essential tools, AI assistance, and interactive learning features in one beautiful interface.

![Study Platform](https://img.shields.io/badge/Study-Platform-blue) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![AI Powered](https://img.shields.io/badge/AI-Powered-green)

## ✨ Features

### 🔧 **Essential Study Tools**
- **🧮 Calculator**: Advanced scientific calculator with trigonometric functions
- **📝 Notepad**: Auto-saving notepad with word count and local storage
- **⏱️ Timer**: Countdown timer and stopwatch with lap functionality
- **🤖 AI Study Assistant**: Powered by Google Gemini API for instant help

### 📚 **Content Management**
- **📄 Study Materials**: Add and organize materials with Google Drive integration
- **🎥 Lecture Library**: YouTube lecture management with embedded player
- **📋 Category System**: Organize content by PYQs, assignments, notes, and lab manuals

### 🎯 **Interactive Learning**
- **🃏 Flashcards**: Create, study, and manage custom flashcards with categories
- **🧠 AI Quizzes**: Generate custom quizzes on any topic with difficulty levels
- **📊 Study Statistics**: Track your learning progress and activity
- **🔀 Study Modes**: Shuffle, filter, and practice with different modes

### 🔬 **Engineering Simulations**
- **📐 Diagonal Scale Construction**: Interactive scale drawing and measurement
- **🎯 Precision Measurement**: Learn engineering drawing fundamentals

### 🪟 **Floating Windows System**
- **Windows 11-style Interface**: Pop-out any tool into draggable floating windows
- **Multi-tasking**: Use multiple tools simultaneously
- **Taskbar Management**: Minimize, maximize, and manage floating windows
- **Smooth Animations**: Hardware-accelerated drag performance

### 🔍 **Smart Search**
- **Real-time Search**: Instant search across all tools and content
- **Keyboard Shortcuts**: Ctrl+K to focus search, Escape to clear
- **Highlighted Results**: Visual highlighting of matching content

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Google Gemini API key (for AI features)
- Internet connection for AI and YouTube features

### Setup

1. **Clone or Download**
   ```bash
   git clone https://github.com/KingSahil/all-in-one-study.git
   cd all-in-one-study
   ```

2. **Get Google Gemini API Key**
   - Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
   - Sign in with your Google account
   - Create a new API key
   - Copy the API key

3. **Configure API Key**
   - Open `index.html` in a text editor
   - Find line with `const GEMINI_API_KEY = 'YOUR_GEMINI_API_KEY_HERE';`
   - Replace `YOUR_GEMINI_API_KEY_HERE` with your actual API key
   - Save the file

4. **Launch Application**
   - Open `index.html` in your web browser
   - Start using the study platform!

## 🎯 Usage Guide

### Basic Navigation
- **Home**: Main dashboard with all tools
- **Search**: Use the search bar to quickly find tools and content
- **Floating Windows**: Click pop-out buttons (🪟) to open tools in floating windows

### AI Study Assistant
1. Click on "AI Study Assistant" or open it in a floating window
2. Type your question in the chat input
3. Press Enter to send your message
4. Get AI-powered responses with formatted text and explanations

### Study Materials Management
1. Go to "Study Material" section
2. Click "Add New Material"
3. Fill in title, category, Google Drive link, and description
4. Materials are automatically saved and categorized
5. Use filter buttons to view materials by category

### Flashcards System
1. Navigate to "Fun Learning" → "Flashcards"
2. Click "Add New Flashcard"
3. Enter question, answer, and category
4. Use study mode to practice flashcards
5. Track your progress with statistics

### AI Quiz Generation
1. Go to "Fun Learning" → "AI Quizzes"
2. Enter a topic and select difficulty
3. Choose number of questions (1-10)
4. Click "Generate Quiz" to create AI-powered questions
5. Answer questions and view results with scoring

### Floating Windows
1. Click any pop-out button (🪟) next to tool names
2. Tools open in draggable, resizable windows
3. Use window controls to minimize, maximize, or close
4. Drag from the title bar to move windows
5. Multiple tools can run simultaneously

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + K` | Focus search bar |
| `Escape` | Clear search and reset view |
| `Alt + F4` | Close active floating window |
| `Ctrl + F12` | Debug floating window inputs |
| `Enter` | Send message in AI chat |

## 🛠️ Technical Features

### Performance Optimizations
- **Hardware Acceleration**: Smooth dragging with CSS transforms
- **RequestAnimationFrame**: Optimized animations and interactions
- **Local Storage**: Persistent data without server requirements
- **Lazy Loading**: Efficient content loading and management

### Responsive Design
- **Mobile Friendly**: Responsive grid layouts and touch support
- **Cross-browser**: Compatible with all modern browsers
- **Accessibility**: Keyboard navigation and screen reader support

### Data Persistence
- All user data is stored locally in browser localStorage
- No account creation or server setup required
- Data persists between browser sessions
- Export/import functionality for backup

## 🎨 Customization

### Themes and Styling
The application uses CSS custom properties for easy theming:
```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    --background-dark: #0f172a;
    --text-light: #f1f5f9;
}
```

### Adding New Tools
1. Create tool HTML structure in the main section
2. Add tool card to the homepage grid
3. Implement tool functions in JavaScript
4. Add floating window support
5. Update search and navigation systems

## 🔧 Troubleshooting

### Common Issues

**AI Assistant not responding:**
- Check your Google Gemini API key is correctly set
- Ensure you have internet connection
- Verify API key has proper permissions

**Floating windows not opening:**
- Press Ctrl+F12 to debug and fix inputs
- Check browser console for error messages
- Refresh the page and try again

**Inputs not working in floating windows:**
- Use the built-in debug function (Ctrl+F12)
- Type `testFloatingInputs()` in browser console
- Check console logs for detailed debugging info

**Data not saving:**
- Ensure localStorage is enabled in your browser
- Check if you're in private/incognito mode
- Clear browser cache and try again

### Debug Tools
- **Browser Console**: Press F12 and check for error messages
- **Built-in Debugger**: Use Ctrl+F12 to run diagnostic tools
- **Test Functions**: Use `testFloatingInputs()` in console

## 📱 Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 80+ | ✅ Fully Supported |
| Firefox | 75+ | ✅ Fully Supported |
| Safari | 13+ | ✅ Fully Supported |
| Edge | 80+ | ✅ Fully Supported |

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Google Gemini API** for AI-powered assistance
- **YouTube API** for video integration
- **Modern CSS** for beautiful styling and animations
- **Local Storage API** for data persistence

## 📞 Support

If you encounter any issues or have questions:

1. Check the troubleshooting section above
2. Search existing issues on GitHub
3. Create a new issue with detailed description
4. Use the built-in debug tools for technical issues

---

**Made with ❤️ for students by students**

*Happy studying! 📚✨*