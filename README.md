# Nepali TTS Studio 🇳🇵

A lightweight, zero-dependency web application that converts Nepali text into natural-sounding speech using the Google Gemini API. 

Built entirely with client-side technologies, this tool allows users to generate high-fidelity audio without requiring complex backend infrastructure or servers.

<img width="953" height="888" alt="image" src="https://github.com/user-attachments/assets/4b13c119-2574-452a-b9b3-abc9bff1fae8" />


## ✨ Features

* **Zero Backend:** Runs entirely in the browser. No server setup, Node.js, or databases required.
* **Multiple Voice Profiles:** Choose from various pre-built Gemini voice profiles:
  * *Kore* (Firm / Clear)
  * *Aoede* (Breezy / Natural)
  * *Zephyr* (Bright / Engaging)
  * *Puck* (Upbeat)
  * *Fenrir* (Excitable)
  * *Leda* (Youthful)
* **Speed Control:** Adjust the pacing of the generated speech (Slow, Normal, Fast).
* **Direct Export:** Generates high-quality WAV files using the Web Audio API that can be downloaded locally.
* **Secure API Handling:** API keys are entered directly by the user on the client side and are never stored or transmitted to external servers other than Google's secure endpoints.

## 🚀 Live Demo

[View the Live Demo Here](https://ficcc.github.io/nepali-tts/) 
*(Update this link with your actual GitHub Pages URL)*

## 🔑 How to Get a Free Gemini API Key

To use this application, you need your own Google Gemini API key. It is completely free to generate one.

1. Go to **[Google AI Studio](https://aistudio.google.com/app/apikey)**.
2. Sign in with your regular Google/Gmail account.
3. Click the blue **"Create API Key"** button.
4. If you don't have an existing Google Cloud project, select **"Create API key in a new project"**.
5. Copy the generated key (it usually starts with `AIzaSy...`).
6. Paste this key into the API key field in the Nepali TTS Studio app.

> **Security Note:** This application connects directly to the Google Gemini API from the browser. **Do not hardcode or commit your personal API key into this public repository.** The app is deliberately designed to ask the user to provide their key during the session so your credentials stay secure.

## 🛠️ Technical Stack

* **Frontend:** HTML5, Vanilla JavaScript
* **Styling:** Tailwind CSS (via CDN)
* **API:** Google Gemini API (`gemini-2.5-flash-preview-tts`)
* **Audio Processing:** Native Web Audio API / PCM to WAV Blob conversion

## 💻 Local Development & Usage

Because this app runs entirely in the browser, there are no build steps or package managers required.

1. Clone the repository:
   ```bash
   git clone [https://github.com/](https://github.com/)[YOUR-USERNAME]/nepali-tts.git
