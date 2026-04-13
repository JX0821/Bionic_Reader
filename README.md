# Bionic_Reader
Finished in 2024

A **bionic reading** tool with **text-to-speech**, designed to help people with dyslexia and anyone who wants to read faster and more comfortably.

Bionic reading works by bolding the first half of each word, allowing your eyes to glide through text more naturally — your brain fills in the rest.

> **th**is **i**s **wh**at **bion**ic **read**ing **loo**ks **li**ke

## ✨ Features

- **GPT Mode** — Uses OpenAI API (`gpt-4o-mini`) to intelligently format text into bionic reading style
- **Local Mode** — 100% offline bionic formatting, no API key needed
- **Text-to-Speech** — Built-in browser TTS with voice selection and speed control
- **Word Tracking** — Highlights the current word being read in real-time
- **Zero Setup** — Single HTML file, no build tools, no dependencies, no framework
- **API Key Persistence** — Your OpenAI key is saved locally in the browser (never sent anywhere except OpenAI)

## 🚀 Quick Start

### Just open it

Download `index.html` and open it in your browser. That's it.

## 📖 Usage

1. **Paste your text** into the input area
2. **Choose a mode**:
   - **GPT (API)** — Enter your OpenAI API key for AI-powered formatting
   - **Local (Free)** — No key needed, runs entirely in your browser
3. **Click Play** — Text is formatted in bionic style and read aloud
4. **Adjust speed** with the slider, pick a voice from the dropdown
5. **Pause / Stop** anytime

## 🔑 About the API Key

- GPT mode requires an [OpenAI API key](https://platform.openai.com/api-keys)
- The key is stored in your browser's `localStorage` only
- It is sent directly to OpenAI's API and nowhere else
- You can use **Local mode** without any key at all

## 🧠 What is Bionic Reading?

Bionic reading is a method that highlights the beginning of words to guide your eyes. Research suggests this can help:

- People with **dyslexia** focus on text more easily
- Speed readers process text faster
- Anyone reduce eye strain during long reading sessions

In this tool, the first half of each word (rounded up) is displayed in bold:

| Original | Bionic |
|----------|--------|
| Reading | **Rea**ding |
| is | **i**s |
| easier | **eas**ier |
| this | **th**is |
| way | **wa**y |

## 🛠 Tech Stack

- **HTML / CSS / JS** — Single file, vanilla, no build step
- **OpenAI API** — `gpt-4o-mini` for intelligent bionic formatting
- **Web Speech API** — Browser-native text-to-speech
- **Google Fonts** — Outfit + JetBrains Mono

## 📂 Project Structure

```
bionic-reader/
└── index.html    ← the entire app
```

Yes, it's just one file.

## 🤝 Contributing

Contributions are welcome! Some ideas:

- [ ] Dark / light theme toggle
- [ ] File upload support (paste a PDF or .txt)
- [ ] Keyboard shortcuts (Space = play/pause, Esc = stop)
- [ ] Export bionic-formatted text as HTML
- [ ] Support for more languages and models
- [ ] Adjustable bold ratio (e.g. first 30% vs 50% of each word)

## 📄 License

MIT — do whatever you want with it.

---

**If this tool helps you or someone you know, consider giving it a ⭐**
