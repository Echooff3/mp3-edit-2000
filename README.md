# 🎵 MP3 Edit 2000

A modern, mobile-friendly web application for editing MP3 metadata and album art directly in your browser.

## 🌐 Live Demo

**[Try it now on GitHub Pages!](https://echooff3.github.io/mp3-edit-2000/)**

## 📦 Available Versions

### Main Version (index.html)
Uses **music-metadata-browser** for reading and **browser-id3-writer** for writing MP3 metadata. This is the recommended version with modern ES modules.

### Alternative Version (index-v2.html)
A **pure JavaScript implementation** with custom ID3v2 parser and writer. No external dependencies for metadata processing. Use this if you experience issues with CDN-hosted libraries.

## ✨ Features

### 📱 Mobile-First Design
- Clean black and white theme optimized for mobile devices
- Responsive layout that works on any screen size
- Touch-friendly interface with large buttons and inputs

### 🎼 MP3 Metadata Editing
- Edit all standard ID3 tags:
  - Title
  - Artist
  - Album
  - Year
  - Genre
  - Comment
  - Track Number
- Load existing metadata from MP3 files
- Save edited MP3 files with new metadata

### 🖼️ Album Art Management
- Upload custom album art (JPEG/PNG)
- View existing album art from MP3 files
- Embed album art directly into MP3 files

### 💾 Template System with IndexedDB
- Save metadata as reusable templates
- Quick-fill metadata fields from saved templates
- Store unlimited templates locally in your browser
- Delete templates you no longer need

### 🔒 Privacy-Focused
- All processing happens locally in your browser
- No files uploaded to any server
- Your data never leaves your device

## 🚀 Technology Stack

### Main Version (index.html)
- **Pure HTML5, CSS3, and JavaScript** - No build process required
- **[music-metadata-browser](https://github.com/Borewit/music-metadata-browser)** - Modern library for reading MP3 metadata
- **[browser-id3-writer](https://github.com/egoroof/browser-id3-writer)** - Writing MP3 metadata
- **IndexedDB** - Local storage for templates
- **GitHub Pages** - Static hosting

### Alternative Version (index-v2.html)
- **Pure JavaScript** - Custom ID3v2.3 parser and writer
- **No external dependencies** for MP3 processing
- **IndexedDB** - Local storage for templates
- **Fully offline-capable** - Works without CDN access

## 💻 Usage

1. **Open the app** in your mobile browser
2. **Choose an MP3 file** from your device
3. **Edit the metadata** fields as needed
4. **Add album art** (optional)
5. **Save the MP3** with your changes
6. **Save as template** to reuse metadata for future files

## 🛠️ Local Development

Simply open `index.html` in your browser - no build process or dependencies required!

## 📄 License

Open source project - feel free to use and modify as needed.
