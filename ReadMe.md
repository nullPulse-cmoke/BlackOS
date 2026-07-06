# BlackOS - Web Desktop in macOS Style

BlackOS is a full-featured web-based operating system simulation with a macOS-like interface, built entirely with HTML, CSS, and JavaScript. The project demonstrates the power of web technologies in creating interactive desktop environments right in your browser.

## 🚀 Features

### 🖥️ Interface
- Boot screen with animated progress bar
- Login screen with avatar and login button
- Menu Bar with clock, Wi-Fi indicator, and system menu
- Desktop with icons and ability to create new folders
- Dock panel with quick access to applications and icon magnification on hover

### 📱 Applications
| Application | Description |
|-------------|-------------|
| Finder | File manager with sidebar and folder browsing |
| Browser | Built-in browser with search (SearXNG) and navigation history |
| Terminal | Command line with support for commands: help, clear, date, whoami, neofetch, ip, ping |
| Calculator | Full-featured calculator with basic operations |
| Settings | Three tabs: wallpapers, system information, application management |

### ⚙️ New Features in Settings (v2026.07)
**System Tab**
- Display OS, kernel, and architecture information
- System uptime indicator
- Restart and shutdown buttons

**Applications Tab**
- List of all applications with status indicators
- Toggle switches for demo application state management

### 🎨 Visual Effects
- Glassmorphism with blur and transparency effects
- Window animations (scaling, fade-in)
- Desktop wallpaper switching capability
- Drag & drop window movement

### 🛠️ Technologies
- HTML5 — Interface structure
- CSS3 — Styling, animations, responsiveness
- Vanilla JavaScript — All application and system logic
- Unsplash API — Background images for wallpapers

## 📦 Installation & Launch

### Local Launch
1. Download the `index.html` file
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Wait for the loading animation and click "Login"

### Online Version
Project available at: [link to your host]

## 🎮 Controls

### Keyboard Shortcuts
- **Enter** — Confirm input (Terminal, Browser)

### Mouse
- Click on icon — Open application
- Drag window title — Move window
- Hover over Dock — Icon magnification

## 📂 Virtual Directory Structure
```
/ (root)
├── Favorites/
│   ├── Projects/
│   └── Photos/
└── Documents/
    ├── notes.txt
    └── todo.md
```

## 🔍 Search Engine
The browser uses SearXNG search engine through the wukko.me proxy:
- Internet search via address bar or homepage
- Direct URL navigation support

## 🧪 Testing
The project has been tested in:
- Chrome 120+
- Firefox 121+
- Safari 17+
- Edge 120+

## 📝 Terminal Commands
| Command | Description |
|---------|-------------|
| help | List available commands |
| clear | Clear terminal screen |
| date | Current date and time |
| whoami | Current username |
| neofetch | System information |
| ip | Local IP address |
| ping | Network connectivity test |

## ⚠️ Known Limitations
- **Browser**: iframe may block loading of some websites due to CORS policy
- **File System**: Fully virtual, no real file access
- **Wallpapers**: Internet connection required to load images

## 🚧 Development Roadmap
- Add text editor
- Implement system tray with notifications
- Add theme switching (light/dark mode)
- Integrate media player
- Create application store

## 🤝 Contributing
If you'd like to improve BlackOS:

1. Fork the repository
2. Make your changes
3. Create a Pull Request

## 📄 License
MIT License — Free use, modification, and distribution.

## 🌟 Support
If you like the project, please ⭐ it on GitHub!

---
**Version:** v2026.07
**Developer:** BlackOS Team
**Release Date:** July 6, 2026

*"The web desktop of tomorrow is here today!"*
