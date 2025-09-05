# German Learning - Multi-Deck System

## 🚀 Professional Multi-Deck Language Learning App

This comprehensive German learning application contains **1 complete decks** with interactive flashcards, speech recognition, and progress tracking.

## 🎯 Features

### 🏠 **Deck Selection Homepage**
- Browse all 1 decks with search and filtering
- Track progress across all decks
- Professional deck organization by level and topic

### 🎴 **Interactive Flashcards**
- Audio playback for German and English
- Grammar analysis with dropdown questions
- Speech recognition for pronunciation practice
- Voice recording and playback
- Practice text areas with validation
- Smart scoring system (0-100 points)

### 🎤 **Advanced Speech Features**
- Real-time speech recognition
- Record and playback your pronunciation
- Compare with target German audio
- Automatic temporary file cleanup
- Works on desktop and tablet

### 📊 **Progress Tracking**
- Individual card scoring
- Deck completion tracking
- Overall progress statistics
- Performance analytics

## 🌐 Deployment

### **Netlify (Recommended)**
1. Drag this entire folder to netlify.com
2. Your app will be live in 30 seconds
3. Get a professional URL like: `https://german-learning-app.netlify.app`

### **Other Platforms**
- **Vercel**: Connect GitHub repository for automatic deployments
- **GitHub Pages**: Upload to repository and enable Pages
- **Firebase Hosting**: Use Firebase CLI to deploy

## 📁 File Structure

```
multi_deck_app/
├── index.html              # Main application
├── netlify.toml            # Deployment configuration  
├── decks/                  # Deck data files
│   ├── manifest.json       # Deck index
│   ├── deck-1.json        # Individual deck data
│   └── ...
└── audio/                  # Audio files organized by deck
    ├── deck-1/
    │   ├── pair_001_english.mp3
    │   ├── pair_001_german.mp3
    │   └── ...
    └── ...
```

## 💰 Hosting Costs

- **Netlify Free**: Perfect for this app (100GB bandwidth/month)
- **Storage**: ~2.5GB total (audio files)
- **Bandwidth**: Free tier covers hundreds of users
- **Custom Domain**: Optional ($12/year)

## 🎮 Usage Instructions

### **Deck Selection**
- Use search bar to find specific topics
- Filter by difficulty level (Beginner/Intermediate/Advanced)
- Click "🚀 Start Learning" to begin any deck

### **Studying**
- **Audio**: Click 🎵 buttons to hear pronunciation
- **Grammar**: Answer dropdown questions for points
- **Speech**: Click 🎤 to practice pronunciation
- **Recording**: Use 🔊 to hear your own voice
- **Navigation**: Use arrow keys or buttons
- **Scoring**: Get real-time feedback on performance

### **Keyboard Shortcuts**
- **← →**: Navigate between cards
- **Escape**: Return to deck selection
- **Spacebar**: Free for typing (no conflicts)

## 🔧 Technical Details

### **Speech Recognition**
- **Supported Browsers**: Chrome, Edge, Safari
- **Languages**: German (de-DE)
- **Privacy**: All processing happens locally
- **Recording**: Temporary storage, auto-deleted

### **Audio Support**
- **Format**: MP3
- **Quality**: Optimized for web delivery
- **Caching**: Aggressive caching for performance
- **Offline**: Works after initial load

### **Data Storage**
- **User Progress**: Browser localStorage
- **Recordings**: Temporary Blob storage
- **Privacy**: No data sent to servers
- **Backup**: Users can export progress

## 🌍 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Edge (excellent speech support)
- ✅ Safari (good on Mac/iOS)
- ✅ Firefox (limited speech recognition)

## 📱 Mobile Support

- **Responsive Design**: Works on all screen sizes
- **Touch Optimized**: Large buttons for mobile
- **Speech Recognition**: Limited on mobile browsers
- **Audio Playback**: Full support on mobile

## 🎊 Perfect for

- **Personal Learning**: Self-study German
- **Educational Institutions**: Classroom use
- **Language Tutors**: Student assignments
- **Study Groups**: Shared learning resource

## 🔄 Updates

To update flashcards:
1. Re-run the Python script with new audio files
2. Upload the new folder to Netlify
3. Changes are live immediately

---

**Enjoy your German learning journey!** 🇩🇪

Created with ❤️ using OpenAI Whisper + GPT-3.5 + Web Technologies
