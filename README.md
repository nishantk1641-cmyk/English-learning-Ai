# AI English Guru 📚
### हिंदी माध्यम के बच्चों के लिए AI English Learning App (Class 1–8)

A complete, offline-capable English learning web app designed specially for Hindi-medium students of Classes 1 to 8.

---

## ✨ Features

- **Soft Male AI Tutor Voice** – Uses browser Speech Synthesis with preferred male English voices
- **Class-wise Content** (1 to 8)
  - Alphabet with pictures & Hindi meaning
  - Vocabulary (शब्द)
  - Grammar (व्याकरण)
  - Sentences (वाक्य)
  - Moral Stories (कहानियाँ)
  - Interactive Quizzes
- **AI Tutor Chat** – Talk in Hindi or English, get helpful replies
- **Progress Tracking** – Saves quiz scores locally
- **Beautiful Child-friendly UI** – Big buttons, clear Hindi labels
- **Works Offline** – No internet needed after loading (except voice may need first load)
- **PWA Ready** – Can be installed on mobile home screen

---

## 🚀 How to Run

### Method 1: Simple
1. Unzip the folder
2. Open `index.html` in any modern browser (Chrome / Edge / Firefox recommended)
3. Allow microphone/speech if asked (for better voice)

### Method 2: Local Server (Recommended for full features)
```bash
# Using Python
cd english-learning-app
python -m http.server 8000

# Or using Node
npx serve .
```
Then open http://localhost:8000

### Mobile
- Open in Chrome → Menu → “Add to Home Screen”
- It will work like a real app

---

## 📁 File Structure

```
english-learning-app/
├── index.html          # Main HTML
├── manifest.json       # PWA manifest
├── README.md
├── css/
│   └── style.css       # All styles
├── js/
│   ├── app.js          # Main application logic
│   ├── speech.js       # Soft male voice module
│   └── data.js         # All lessons, quizzes, stories
└── assets/             # (empty – ready for future images)
```

---

## 🎯 How Students Use It

1. Open the app → Tap **शुरू करें**
2. Select your **Class (1–8)**
3. Choose what to learn:
   - Alphabet
   - Vocabulary
   - Grammar
   - Sentences
   - Stories
   - Quiz
   - AI Tutor (chat)
4. Tap any word/sentence to hear soft male voice pronunciation
5. Take quizzes and track progress

---

## 🔊 Voice Settings

- Go to ⚙️ Settings
- Change speaking speed
- Choose different English voice (if available on device)
- Turn Auto-speak on/off

**Tip:** On Android Chrome, “Google UK English Male” or “Microsoft David” gives the softest male voice.

---

## 🛠️ Technology

- Pure HTML + CSS + JavaScript (no framework)
- Web Speech API for voice
- localStorage for progress
- Fully responsive (mobile-first)

---

## 👨‍🏫 For Teachers / Parents

You can easily edit content by opening `js/data.js` and changing:
- Vocabulary lists
- Grammar topics
- Sentences
- Stories
- Quiz questions

---

Made with ❤️ for Hindi-medium students of India.
**AI English Guru** – Learn English the smart & fun way!
