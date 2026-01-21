<div align="center">

# 📝 Smart Note-Taking Application

### Modern, Fast, and Intuitive Note Management System

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![React](https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://reactjs.org/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**A feature-rich, lightweight note-taking application with local storage, rich text editing, and intuitive UI. Perfect for capturing ideas, managing tasks, and organizing thoughts.**

[Features](#-features) • [Demo](#-live-demo) • [Installation](#-installation) • [Usage](#-usage) • [Screenshots](#-screenshots)

---

![App Banner](https://via.placeholder.com/1000x400/4A90E2/FFFFFF?text=Smart+Note-Taking+Application)

</div>

---

## 📌 Overview

**Smart Note-Taking Application** is a modern, minimalist note management system designed for productivity enthusiasts. Built with vanilla JavaScript (or React), it offers a seamless note-taking experience with automatic saving, search functionality, and an elegant user interface.

### 🎯 Why This App?

- ⚡ **Lightning Fast** - No backend delays, instant response
- 🔒 **Privacy First** - All data stored locally in your browser
- 💾 **Auto-Save** - Never lose your work with automatic saving
- 🎨 **Beautiful UI** - Clean, modern interface with dark mode
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile
- 🚀 **Zero Setup** - No registration, no installation, just start writing
- 🔍 **Smart Search** - Find your notes instantly
- 🏷️ **Categories & Tags** - Organize notes efficiently

---

## ✨ Key Features

### Core Functionality
- ✅ **Create, Read, Update, Delete (CRUD)** - Full note management
- ✅ **Rich Text Editor** - Format text with bold, italic, underline, lists
- ✅ **Auto-Save** - Automatic saving as you type
- ✅ **Local Storage** - No database required, works offline
- ✅ **Search & Filter** - Quickly find notes by title or content
- ✅ **Pin Important Notes** - Keep crucial notes at the top
- ✅ **Color Coding** - Assign colors to categorize notes

### Advanced Features
- 📊 **Note Statistics** - Track total notes, words, characters
- 🔖 **Categories/Tags** - Organize notes with custom tags
- 📅 **Timestamps** - Automatic creation and modification dates
- 🌓 **Dark/Light Mode** - Eye-friendly themes
- 📤 **Export/Import** - Backup and restore notes (JSON format)
- ⭐ **Favorites** - Mark important notes
- 🗑️ **Trash/Archive** - Soft delete with recovery option
- 📋 **Duplicate Notes** - Quick copy functionality

### User Experience
- 🎯 **Keyboard Shortcuts** - Efficient navigation
- 📱 **Mobile Optimized** - Touch-friendly interface
- ⚡ **Fast Performance** - Optimized for speed
- 🎨 **Customizable** - Choose themes and layouts
- 🔔 **Notifications** - Success/error messages

---

## 🛠️ Tech Stack

### Frontend
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)

### Storage
![LocalStorage](https://img.shields.io/badge/-LocalStorage-FF6B6B?style=flat-square)
![IndexedDB](https://img.shields.io/badge/-IndexedDB-4A90E2?style=flat-square)

### Tools & Libraries
![Markdown](https://img.shields.io/badge/-Markdown-000000?style=flat-square&logo=markdown&logoColor=white)
![FontAwesome](https://img.shields.io/badge/-Font%20Awesome-339AF0?style=flat-square&logo=font-awesome&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 🚀 Live Demo

### 🌐 Try it Now!
**Live Demo:** [https://your-note-app.netlify.app](https://your-note-app.netlify.app)

**Test Features:**
- Create your first note
- Try the search functionality
- Toggle dark/light mode
- Export and import notes
- Use keyboard shortcuts (Ctrl+N for new note)

---

## 📋 Prerequisites

**For Basic HTML/CSS/JS Version:**
```bash
Any modern web browser (Chrome, Firefox, Safari, Edge)
No installation required!
```

**For React Version:**
```bash
Node.js >= 14.x
npm or yarn
```

---

## ⚙️ Installation & Setup

### Option 1: Simple HTML Version (Recommended for Beginners)

```bash
# Clone the repository
git clone https://github.com/Allanagari-Renuka/Note-Taking-App.git
cd Note-Taking-App

# Open in browser
# Simply double-click index.html
# Or use Live Server in VS Code
```

### Option 2: React Version

```bash
# Clone the repository
git clone https://github.com/Allanagari-Renuka/Note-Taking-App.git
cd Note-Taking-App

# Install dependencies
npm install

# Start development server
npm start

# Build for production
npm run build
```

### Option 3: Using Live Server (VS Code)

```bash
# Install Live Server extension in VS Code
# Right-click on index.html
# Select "Open with Live Server"
```

---

## 💻 Usage Guide

### Creating Your First Note

1. **Click "New Note" button** or press `Ctrl+N`
2. **Enter a title** for your note
3. **Write your content** in the text area
4. **Note saves automatically** as you type
5. **Close or navigate away** - your note is saved!

### Organizing Notes

```javascript
// Add a category
- Click the tag icon
- Enter category name
- Press Enter

// Search notes
- Type in the search bar
- Results filter in real-time

// Pin important notes
- Click the pin icon
- Note moves to top of list
```

### Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl + N` | Create new note |
| `Ctrl + S` | Save note (manual) |
| `Ctrl + F` | Focus search bar |
| `Ctrl + D` | Delete current note |
| `Ctrl + E` | Edit current note |
| `Esc` | Close note editor |
| `Ctrl + ,` | Open settings |

---

## 📁 Project Structure

```
Note-Taking-App/
│
├── index.html                 # Main HTML file
├── styles.css                 # Main stylesheet
├── script.js                  # Core JavaScript logic
│
├── assets/                    # Static assets
│   ├── icons/                # App icons
│   ├── images/               # Images and screenshots
│   └── fonts/                # Custom fonts
│
├── css/                      # Additional stylesheets
│   ├── themes.css           # Dark/Light themes
│   ├── responsive.css       # Mobile responsiveness
│   └── animations.css       # Animations
│
├── js/                       # JavaScript modules
│   ├── storage.js           # LocalStorage management
│   ├── noteManager.js       # Note CRUD operations
│   ├── search.js            # Search functionality
│   ├── export.js            # Export/Import features
│   └── utils.js             # Utility functions
│
├── components/               # React components (if using React)
│   ├── NoteList.jsx
│   ├── NoteEditor.jsx
│   ├── SearchBar.jsx
│   └── Sidebar.jsx
│
├── screenshots/              # App screenshots
├── README.md                # Project documentation
├── LICENSE                  # MIT License
└── .gitignore              # Git ignore file
```

---

## 🎨 Core Features Implementation

### 1. Local Storage Management

```javascript
// storage.js
class NoteStorage {
  constructor() {
    this.storageKey = 'smartNotes';
  }

  // Get all notes
  getAllNotes() {
    const notes = localStorage.getItem(this.storageKey);
    return notes ? JSON.parse(notes) : [];
  }

  // Save note
  saveNote(note) {
    const notes = this.getAllNotes();
    const existingIndex = notes.findIndex(n => n.id === note.id);
    
    if (existingIndex >= 0) {
      notes[existingIndex] = note;
    } else {
      notes.push(note);
    }
    
    localStorage.setItem(this.storageKey, JSON.stringify(notes));
    return note;
  }

  // Delete note
  deleteNote(noteId) {
    const notes = this.getAllNotes();
    const filtered = notes.filter(n => n.id !== noteId);
    localStorage.setItem(this.storageKey, JSON.stringify(filtered));
  }

  // Search notes
  searchNotes(query) {
    const notes = this.getAllNotes();
    return notes.filter(note => 
      note.title.toLowerCase().includes(query.toLowerCase()) ||
      note.content.toLowerCase().includes(query.toLowerCase())
    );
  }
}

const storage = new NoteStorage();
export default storage;
```

### 2. Note Manager

```javascript
// noteManager.js
class Note {
  constructor(title = '', content = '', category = '', color = '#fff') {
    this.id = Date.now().toString();
    this.title = title;
    this.content = content;
    this.category = category;
    this.color = color;
    this.createdAt = new Date().toISOString();
    this.updatedAt = new Date().toISOString();
    this.isPinned = false;
    this.isFavorite = false;
  }

  update(data) {
    Object.assign(this, data);
    this.updatedAt = new Date().toISOString();
  }
}

class NoteManager {
  constructor() {
    this.notes = storage.getAllNotes();
    this.currentNote = null;
  }

  createNote(title, content, category, color) {
    const note = new Note(title, content, category, color);
    this.notes.push(note);
    storage.saveNote(note);
    return note;
  }

  updateNote(noteId, updates) {
    const note = this.notes.find(n => n.id === noteId);
    if (note) {
      note.update(updates);
      storage.saveNote(note);
    }
    return note;
  }

  deleteNote(noteId) {
    this.notes = this.notes.filter(n => n.id !== noteId);
    storage.deleteNote(noteId);
  }

  togglePin(noteId) {
    const note = this.notes.find(n => n.id === noteId);
    if (note) {
      note.isPinned = !note.isPinned;
      storage.saveNote(note);
    }
  }

  getSortedNotes() {
    return this.notes.sort((a, b) => {
      if (a.isPinned && !b.isPinned) return -1;
      if (!a.isPinned && b.isPinned) return 1;
      return new Date(b.updatedAt) - new Date(a.updatedAt);
    });
  }
}

const noteManager = new NoteManager();
export default noteManager;
```

### 3. Auto-Save Implementation

```javascript
// Auto-save functionality
let saveTimeout;
const AUTO_SAVE_DELAY = 1000; // 1 second

function autoSave(noteId, title, content) {
  // Clear previous timeout
  clearTimeout(saveTimeout);
  
  // Set new timeout
  saveTimeout = setTimeout(() => {
    noteManager.updateNote(noteId, { title, content });
    showNotification('Note saved', 'success');
  }, AUTO_SAVE_DELAY);
}

// Usage in event listener
document.getElementById('noteContent').addEventListener('input', (e) => {
  const noteId = currentNote.id;
  const content = e.target.value;
  const title = document.getElementById('noteTitle').value;
  
  autoSave(noteId, title, content);
});
```

### 4. Search Functionality

```javascript
// search.js
function searchNotes(query) {
  const searchResults = noteManager.notes.filter(note => {
    const titleMatch = note.title.toLowerCase().includes(query.toLowerCase());
    const contentMatch = note.content.toLowerCase().includes(query.toLowerCase());
    const categoryMatch = note.category.toLowerCase().includes(query.toLowerCase());
    
    return titleMatch || contentMatch || categoryMatch;
  });
  
  displayNotes(searchResults);
}

// Real-time search
document.getElementById('searchInput').addEventListener('input', (e) => {
  const query = e.target.value;
  searchNotes(query);
});
```

### 5. Export/Import Functionality

```javascript
// export.js
function exportNotes() {
  const notes = noteManager.getAllNotes();
  const dataStr = JSON.stringify(notes, null, 2);
  const dataBlob = new Blob([dataStr], { type: 'application/json' });
  
  const url = URL.createObjectURL(dataBlob);
  const link = document.createElement('a');
  link.href = url;
  link.download = `notes-backup-${new Date().toISOString()}.json`;
  link.click();
  
  URL.revokeObjectURL(url);
  showNotification('Notes exported successfully!', 'success');
}

function importNotes(file) {
  const reader = new FileReader();
  
  reader.onload = (e) => {
    try {
      const importedNotes = JSON.parse(e.target.result);
      
      importedNotes.forEach(note => {
        storage.saveNote(note);
      });
      
      noteManager.notes = storage.getAllNotes();
      displayNotes(noteManager.getSortedNotes());
      showNotification(`${importedNotes.length} notes imported!`, 'success');
    } catch (error) {
      showNotification('Error importing notes', 'error');
    }
  };
  
  reader.readAsText(file);
}
```

---

## 📸 Screenshots

<div align="center">

### Main Dashboard
![Dashboard](screenshots/dashboard.png)

### Note Editor
![Editor](screenshots/editor.png)

### Search Functionality
![Search](screenshots/search.png)

### Dark Mode
![Dark Mode](screenshots/dark-mode.png)

### Mobile View
![Mobile](screenshots/mobile.png)

</div>

---

## 🎨 Customization

### Changing Theme Colors

```css
/* In styles.css or themes.css */
:root {
  /* Light Mode */
  --primary-color: #4A90E2;
  --secondary-color: #50C878;
  --background-color: #F5F7FA;
  --text-color: #333333;
  --card-background: #FFFFFF;
  --border-color: #E1E8ED;
}

[data-theme="dark"] {
  /* Dark Mode */
  --primary-color: #5B9FED;
  --secondary-color: #5FD88F;
  --background-color: #1A1A2E;
  --text-color: #E0E0E0;
  --card-background: #16213E;
  --border-color: #0F3460;
}
```

### Adding Custom Categories

```javascript
// Define custom categories
const categories = [
  { name: 'Personal', color: '#FF6B6B', icon: '👤' },
  { name: 'Work', color: '#4ECDC4', icon: '💼' },
  { name: 'Ideas', color: '#FFE66D', icon: '💡' },
  { name: 'Todo', color: '#95E1D3', icon: '✅' },
  { name: 'Important', color: '#FF8B94', icon: '⭐' }
];
```

---

## 🚀 Deployment

### Deploy to Netlify (Recommended)

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Ready for deployment"
   git push origin main
   ```

2. **Connect to Netlify**
   - Go to [Netlify](https://www.netlify.com/)
   - Click "New site from Git"
   - Select your repository
   - Click "Deploy site"

### Deploy to GitHub Pages

```bash
# Enable GitHub Pages in repository settings
# Select branch: main
# Select folder: / (root) or /docs

# Access at: https://your-username.github.io/Note-Taking-App
```

### Deploy to Vercel

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel

# Follow the prompts
```

---

## 🔮 Future Enhancements

### Phase 1 (Next Month)
- [ ] **Markdown Support** - Write notes in Markdown
- [ ] **Voice Notes** - Record audio notes
- [ ] **Image Upload** - Attach images to notes
- [ ] **Checklist/Todo** - Add checkbox lists

### Phase 2 (Next 3 Months)
- [ ] **Cloud Sync** - Firebase/Supabase integration
- [ ] **Collaboration** - Share notes with others
- [ ] **Version History** - Track note changes
- [ ] **Reminders** - Set reminders for notes

### Phase 3 (Next 6 Months)
- [ ] **Mobile Apps** - React Native iOS/Android apps
- [ ] **Desktop App** - Electron desktop application
- [ ] **AI Features** - Smart categorization, summaries
- [ ] **Encryption** - End-to-end encryption option

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Ways to Contribute
1. 🐛 Report bugs
2. 💡 Suggest new features
3. 📝 Improve documentation
4. 🎨 Enhance UI/UX
5. 🧪 Add tests

### Contribution Process

```bash
# Fork the repository
git clone https://github.com/your-username/Note-Taking-App.git

# Create feature branch
git checkout -b feature/AmazingFeature

# Make changes and commit
git commit -m 'Add some AmazingFeature'

# Push to branch
git push origin feature/AmazingFeature

# Open Pull Request
```

---

## 🐛 Known Issues

- [ ] Long notes may have performance issues (>10,000 characters)
- [ ] Search doesn't support regex yet
- [ ] Export doesn't include formatting

See [Issues](https://github.com/Allanagari-Renuka/Note-Taking-App/issues) for more details.

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Allanagari Renuka**

Full Stack Developer | Building Productivity Tools

- 🌐 **Portfolio:** [portfolio-beige-two-49.vercel.app](https://portfolio-beige-two-49.vercel.app/)
- 💼 **LinkedIn:** [Connect with me](YOUR_LINKEDIN_URL)
- 📧 **Email:** [allanagarirenuka28@gmail.com](mailto:allanagarirenuka28@gmail.com)
- 🐙 **GitHub:** [@Allanagari-Renuka](https://github.com/Allanagari-Renuka)

---

## 🙏 Acknowledgments

- Icons: [Font Awesome](https://fontawesome.com/)
- Fonts: [Google Fonts](https://fonts.google.com/)
- Inspiration: Notion, Evernote, Google Keep
- Community: Open source contributors

---

## 📞 Support

**Need Help?**

- 📧 **Email:** allanagarirenuka28@gmail.com
- 🐛 **Bug Reports:** [Open an issue](https://github.com/Allanagari-Renuka/Note-Taking-App/issues)
- 💡 **Feature Requests:** [Submit a request](https://github.com/Allanagari-Renuka/Note-Taking-App/issues)

---

<div align="center">

### ⭐ Star this repository if you found it helpful!

![Made with HTML](https://img.shields.io/badge/Made%20with-HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Styled with CSS](https://img.shields.io/badge/Styled%20with-CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Powered by JavaScript](https://img.shields.io/badge/Powered%20by-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Capture your thoughts, organize your life! 📝**

</div>
