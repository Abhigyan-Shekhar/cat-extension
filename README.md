# 🐾 Cat Cursor Theme

A delightful Chrome extension that transforms your browser cursor into adorable cat-themed cursors! 

![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest-V3-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

## ✨ Features

- 🐱 **Cat Paw Cursor**: A cute pink paw appears as your default cursor
- 😺 **Cat Face Cursor**: An adorable cat face shows when hovering over clickable elements
- 🎨 **Beautiful Gradients**: Smooth pink gradients with artistic styling
- 🌐 **Works Everywhere**: Active on all websites you visit
- ⚡ **Lightweight**: SVG-based cursors embedded directly in CSS
- 🎯 **Pixel Perfect**: Optimized hotspot positioning for accurate clicking

## 🎬 Demo

The extension provides two custom cursors:

1. **Default Cursor (Cat Paw)** 🐾
   - Pink paw print design
   - Shows on all standard elements
   
2. **Hover Cursor (Cat Face)** 😺
   - Cute cat face with ears and whiskers
   - Appears on links, buttons, and clickable elements
   - Gradient-filled for a premium look

## 📥 Installation

### From Chrome Web Store
*Coming soon!*

### Manual Installation (Developer Mode)

1. **Download the Extension**
   ```bash
   git clone https://github.com/Abhigyan-Shekhar/cat-extension.git
   ```

2. **Open Chrome Extensions Page**
   - Navigate to `chrome://extensions/`
   - Or click the three dots menu → More Tools → Extensions

3. **Enable Developer Mode**
   - Toggle the "Developer mode" switch in the top right corner

4. **Load the Extension**
   - Click "Load unpacked"
   - Select the extension folder

5. **Enjoy Your Cat Cursors!** 🎉
   - The extension will automatically apply to all websites

## 📁 Project Structure

```
cat-cursor-theme/
├── manifest.json      # Extension configuration (Manifest V3)
├── styles.css         # Custom cursor styles with SVG data URIs
├── popup.html         # Extension popup interface
└── README.md          # This file
```

## 🛠️ Technical Details

- **Manifest Version**: 3 (latest Chrome extension standard)
- **Cursor Format**: SVG Data URIs (embedded directly in CSS)
- **Permissions**: Minimal - only content script injection
- **Size**: Ultra-lightweight (~6KB total)
- **Compatibility**: All Chromium-based browsers (Chrome, Edge, Brave, etc.)

## 🎨 Customization

Want to modify the cursor designs? Edit the SVG data in `styles.css`:

```css
/* Cat Paw Cursor - Default */
body, body *, input, textarea {
  cursor: url('data:image/svg+xml;utf8,...') 16 16, auto !important;
}

/* Cat Face Cursor - Hover */
a, button, [role="button"] {
  cursor: url('data:image/svg+xml;utf8,...') 16 16, pointer !important;
}
```

The numbers `16 16` represent the hotspot position (center of the 32x32 cursor).

## 🐛 Known Issues & Limitations

- Some websites with aggressive CSS overrides may resist custom cursors
- Cursor may not appear in browser UI elements (address bar, tabs, etc.)
- Performance impact is negligible but varies by website complexity

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions

- [ ] Add more cursor variations (sleeping cat, playing cat, etc.)
- [ ] Create a settings page to toggle between cursor styles
- [ ] Add dark mode detection for cursor color adaptation
- [ ] Create animated cursor options
- [ ] Add keyboard shortcuts to toggle extension

## 📝 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2024 Abhigyan Shekhar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👨‍💻 Author

Created with ❤️ by [Abhigyan Shekhar](https://github.com/Abhigyan-Shekhar)

## 🌟 Show Your Support

If you like this project, please give it a ⭐️ on GitHub!

## 📞 Contact & Support

- **Issues**: [GitHub Issues](https://github.com/Abhigyan-Shekhar/cat-extension/issues)
- **GitHub**: [@Abhigyan-Shekhar](https://github.com/Abhigyan-Shekhar)

---

<div align="center">
  Made with 💖 and lots of 🐱
</div>
