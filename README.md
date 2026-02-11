# 🎬 Video Title Maker Web App

A powerful, browser-based video text overlay editor that lets you add, customize, and export text captions to videos without any external plugins or server-side processing.

![Video Text Editor](https://img.shields.io/badge/status-production-ready-green)
![License](https://img.shields.io/badge/license-MIT-blue)
![HTML5](https://img.shields.io/badge/HTML5-✔-orange)
![CSS3](https://img.shields.io/badge/CSS3-✔-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)

## ✨ Features

- **🎯 Pure Browser-Based** - No server required, all processing happens locally
- **📝 Dynamic Text Overlays** - Add multiple text elements with custom timing
- **🎨 Full Text Customization** - Font size, color, style (bold, italic)
- **🖱️ Drag & Resize** - Interactive positioning with visual handles
- **⏱️ Precise Timing Control** - Set start time and duration for each text
- **📋 Text Management** - View, edit, and delete added texts
- **📤 Video Export** - Download final video with burned-in text overlays
- **🎯 Multiple Positioning Options** - Preset positions or custom placement
- **🎨 Modern UI** - Clean, responsive interface with gradient design

## 🚀 Quick Start

1. Clone or download this repository
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari)
3. Click **"Load Video"** to select a video file
4. Click **"Add Text"** to create your first text overlay
5. Customize appearance, timing, and position
6. Click **"Export Video with Texts"** to download the final result

## 📖 How to Use

### Adding Text Overlays
1. Click **"Add Text"** to create a new text element
2. Type your text in the editor panel
3. Adjust font size, color, and style
4. Set start time and duration
5. Choose position (preset or custom)
6. Drag or resize directly on the video

### Managing Texts
- **Select**: Click on any text to edit its properties
- **Delete**: Click the × button next to texts in the sidebar
- **Timeline**: Use the slider to preview texts at different times
- **Visibility**: Texts automatically appear/disappear based on timing

### Exporting
1. Add all desired text overlays
2. Click **"Export Video with Texts"**
3. Wait for processing (progress shown on button)
4. Download will start automatically

## 🛠️ Technical Details

### Architecture
- **Pure HTML5/CSS3/JavaScript** - No dependencies
- **Canvas API** - For rendering text on video frames
- **MediaRecorder API** - For video encoding and export
- **Web Audio API** - For audio extraction and mixing

### Browser Compatibility
| Browser | Support |
|---------|---------|
| Chrome  | ✅ Full |
| Firefox | ✅ Full |
| Edge    | ✅ Full |
| Safari  | ⚠️ Limited (audio extraction may vary) |

### Limitations
- Maximum export resolution: Original video resolution
- Export format: WebM (VP8/VP9 codec)
- Audio extraction: Requires browser Web Audio API support
- Large videos may require more processing time

## 🎯 Use Cases

- **Content Creators** - Add captions to social media videos
- **Educators** - Create annotated instructional videos
- **Marketers** - Brand videos with custom text overlays
- **Personal Use** - Meme creation, video editing
- **Prototyping** - Quick video mockups with text elements

## 🔧 Customization

### Styling
The interface uses CSS variables and can be easily customized:
```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --button-color: #4f46e5;
    --accent-color: #10b981;
}
```

### Adding Features
The code is modular and can be extended with:
- **Multiple text styles** (underline, strikethrough)
- **Animation effects** (fade in/out, slide)
- **More export formats** (MP4 with different codecs)
- **Text shadows and outlines**
- **Templates and presets**

## 📁 Project Structure

```
www/
│
├── index.html          # Main application file
└── assets/             # (Optional) Screenshots and resources
```

## 🚦 Performance Tips

- **Smaller videos** process faster (recommended: <100MB)
- **Fewer text overlays** improve export speed
- **Lower duration** texts reduce rendering complexity
- **Chrome/Edge** offer the best export performance

## 🔜 Future Improvements

- [ ] Text animations and transitions
- [ ] Multiple export formats (MP4, GIF)
- [ ] Save/load project feature
- [ ] Undo/redo functionality
- [ ] Text background boxes
- [ ] Font family selection
- [ ] Batch text import from SRT files
- [ ] Real-time preview during export

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

MIT License - feel free to use this project for personal or commercial purposes.

## ⚠️ Important Notes

- **Privacy** - All processing happens locally; your videos never leave your computer
- **Performance** - Export time depends on video length and number of text overlays
- **Audio** - Some browsers may have limitations in audio extraction
- **File Size** - Exported files are saved in WebM format for optimal compression

## 🙏 Acknowledgments

- Built with vanilla JavaScript - no frameworks harmed
- Inspired by professional video editing tools
- Thanks to the open-source community for Web APIs

---

**Made with ❤️ for content creators everywhere**

*Have suggestions or found a bug? Please open an issue!*