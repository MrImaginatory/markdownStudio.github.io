# Markdown Studio

A lightweight, browser-based Markdown editor with real-time preview, synchronized scrolling, and document analytics.

![Markdown Studio Screenshot](https://via.placeholder.com/800x400?text=Markdown+Studio)

## ✨ Features

- **Live Preview** - Write Markdown on the left, see the rendered result on the right in real-time
- **Sync Scroll** - Editor and preview scroll together for seamless navigation
- **View Controls** - Toggle editor and preview panels independently
- **Dark/Light Mode** - System-aware theme switching
- **Document Analytics** - Built-in analytics sidebar with:
  - Content composition breakdown
  - Reading time estimation
  - Word and paragraph counts
- **File Operations** - Open and save `.md` files directly in the browser
- **Responsive Design** - Works on desktop and mobile devices
- **Zero Dependencies** - No build process required, runs entirely in the browser

## 🚀 Getting Started

### Quick Start

Simply open `MarkDown.html` in any modern web browser:

```bash
# Open in default browser (Windows)
start MarkDown.html

# Open in default browser (macOS)
open MarkDown.html

# Open in default browser (Linux)
xdg-open MarkDown.html
```

That's it! No server, no installation, no dependencies.

### Usage

1. **Write** - Type Markdown in the editor panel on the left
2. **Preview** - See the rendered output on the right panel
3. **Analyze** - Click "Analytics" to open the sidebar with document metrics
4. **Save** - Click "Save" to download your document as a `.md` file
5. **Open** - Click "Open" to load an existing Markdown file

## 🛠️ Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Tailwind CSS for styling (via CDN)
- **JavaScript ES6+** - Vanilla JS, no frameworks
- **Libraries:**
  - [marked.js](https://marked.js.org/) - Markdown parser
  - [Chart.js](https://www.chartjs.org/) - Analytics visualization
  - [Google Fonts](https://fonts.google.com/) - Inter and Fira Code
  - [Material Symbols](https://fonts.google.com/icons) - Icons

## 📖 Markdown Syntax Support

Markdown Studio supports standard Markdown syntax including:

- Headings (# ## ###)
- Bold (**text**) and Italic (*text*)
- Lists (ordered and unordered)
- Links ([text](url))
- Images (![alt](url))
- Code blocks (```code``` and `code`)
- Blockquotes (> text)
- Tables
- Horizontal rules (---)

## ⌨️ Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Toggle Editor | Click the dock_to_left icon |
| Toggle Preview | Click the dock_to_right icon |
| Toggle Sync Scroll | Click the sync_lock icon |
| Toggle Theme | Click the light/dark mode icon |
| Save File | Click the save icon |

## 📱 Browser Support

Tested and works on:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## 📄 License

MIT License - feel free to use, modify, and distribute.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

Made with ❤️ for Markdown lovers
