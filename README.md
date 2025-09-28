# Vibe Playlist 🎵

A single-file web app for discovering music by vibe using the Deezer API. Simply describe your mood or activity, and get instant access to curated tracks with 30-second previews.

## 🚀 Features

### 🔍 **Vibe-Based Music Discovery**
- Search music by describing your mood, activity, or vibe (e.g., "chill coding", "rainy coffee shop", "late night drive")
- Powered by Deezer's extensive music catalog
- Get up to 10 perfectly matched tracks for any vibe

### 🎧 **Audio Preview & Playback**
- Listen to 30-second previews of each track
- Smart single-track playback (only one song plays at a time)
- Easy Play/Pause controls for each track
- Visual feedback for loading and playback states

### 📋 **Playlist Management**
- One-click playlist copying to clipboard
- Formatted playlist with track numbers, titles, and artists
- Perfect for sharing with friends or saving for later

### 💾 **Smart Persistence**
- Automatically saves your last search query
- Resumes where you left off when you return
- Uses browser localStorage for seamless experience

### 🎨 **Simple Design**
- Modern gradient background with glassmorphism effects
- Responsive grid layout that works on all devices
- Clean, minimal interface focused on music discovery
- Smooth hover animations and transitions

### ♿ **Accessibility Features**
- Proper focus states for keyboard navigation
- Disabled button states during loading
- Clear visual feedback for all interactions
- Screen reader friendly structure

## 🛠️ Technical Features

- **Single File Architecture**: Everything in one `index.html` file - no build tools required
- **CORS Proxy Integration**: Seamlessly handles API requests without server setup
- **Mobile Responsive**: Works perfectly on desktop, tablet, and mobile devices

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/iRunTech/Vibe-Playlist.git
   cd Vibe-Playlist
   ```

2. **Open the app:**
   ```bash
   open index.html
   ```
   Or simply double-click `index.html` in your file explorer

3. **Start discovering music:**
   - Enter your vibe in the search box (e.g., "workout motivation", "study focus")
   - Click "Generate" to find matching tracks
   - Listen to previews and copy playlists to share

## 💡 Usage Examples

Try these example vibes to get started:
- `"lofi hip hop study session"`
- `"energetic morning workout"`
- `"relaxing evening jazz"`
- `"driving through the city at night"`
- `"acoustic coffee shop atmosphere"`
- `"retro 80s dance party"`

## 🔧 How It Works

1. **Input Processing**: Takes your natural language vibe description
2. **API Integration**: Queries Deezer's search API through a CORS proxy
3. **Results Display**: Shows album artwork, track info, and playback controls
4. **Audio Management**: Handles preview playback with proper cleanup
5. **Playlist Generation**: Formats results for easy copying and sharing

## 🌐 API & Dependencies

- **Deezer Search API**: Powers music discovery and metadata
- **CORS Proxy**: `corsproxy.io` enables browser-based API calls
- **No External Dependencies**: Pure HTML, CSS, and JavaScript

## 🤝 Contributing

This is a single-file project, making contributions simple:

1. Fork the repository
2. Make your changes to `index.html`
3. Test in multiple browsers
4. Submit a pull request

## 📄 License

Open source project - feel free to fork, modify, and share!
