# 🌐 Webvium Search

<div align="center">

![Webvium Search](https://saksham.thedev.id/Webvium-Search/favicon.png)

**A modern, privacy-focused search portal with multiple search engine options**

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/OshekharO/Webvium-Search.svg)](https://github.com/OshekharO/Webvium-Search/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/OshekharO/Webvium-Search.svg)](https://github.com/OshekharO/Webvium-Search/issues)

[Live Demo](https://saksham.thedev.id/Webvium-Search/) · [Report Bug](https://github.com/OshekharO/Webvium-Search/issues) · [Request Feature](https://github.com/OshekharO/Webvium-Search/issues)

</div>

---

## ✨ Features

- 🔍 **Multiple Search Engines** - Choose from Google, Bing, DuckDuckGo, Brave, Yahoo, Ecosia, You.com, Yep, and Webvium
- 🌙 **Dark Mode** - Automatic dark/light mode based on system preferences
- 💾 **Preference Saving** - Your search engine choice is saved locally
- ⌨️ **Keyboard Shortcuts** - Press `/` to focus search, `Escape` to clear
- 📱 **Responsive Design** - Works beautifully on all devices
- ♿ **Accessible** - Built with WCAG guidelines in mind
- 🚀 **Fast & Lightweight** - No external dependencies

## 🖥️ Screenshots

### Light Mode
The clean, minimalist interface adapts to your system preferences.

### Dark Mode
Easy on the eyes with automatic dark mode support.

## 🚀 Quick Start

### Using as Your Homepage

1. Visit [Webvium Search](https://saksham.thedev.id/Webvium-Search/)
2. Set it as your browser homepage
3. Start searching!

### Self-Hosting

1. Clone the repository:
   ```bash
   git clone https://github.com/OshekharO/Webvium-Search.git
   ```

2. Open `index.html` in your browser, or serve with any static file server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

3. Open `http://localhost:8000` in your browser

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `/` | Focus search input |
| `Enter` | Submit search |
| `Escape` | Clear search / Unfocus |

## 🎨 Customization

### Adding New Search Engines

Edit the `searchEngines` object in `index.html`:

```javascript
const searchEngines = {
  // Add your custom search engine
  custom: { 
    url: 'https://your-search-engine.com/search', 
    name: 'Custom', 
    param: 'q' 
  },
  // ...
};
```

Don't forget to add a corresponding `<option>` in the select element.

### Theming

The CSS uses CSS custom properties (variables) for easy theming. Edit the `:root` section in `style.css`:

```css
:root {
  --color-primary: #4285f4;
  --color-background: #f8f9fa;
  /* ... */
}
```

## 📱 Webvium Browser

This search portal was created for **Webvium**, a sleek, fast, feature-rich Android web browser with Material Design aesthetics.

- 🎨 Beautiful Material Design
- ⚡ Fast and lightweight
- 🔒 Privacy-focused
- 🌐 Full-featured browsing experience

Get involved with the Webvium community on [GitHub](https://github.com/webvium).

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Webvium Browser Team](https://github.com/webvium)
- All the amazing search engines supported
- The open source community

---

<div align="center">

Made with ❤️ by [OshekharO](https://github.com/OshekharO)

**Happy browsing with Webvium!** 🎊🌐💻🚀

</div>
