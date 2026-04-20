# Nepali TTS Studio 🇳🇵

A lightweight, zero-dependency web application that converts Nepali text into natural-sounding speech using the Google Gemini API. 

Built entirely with client-side technologies, this tool allows users to generate high-fidelity audio without requiring complex backend infrastructure or servers.

![Screenshot placeholder - add an image of your app here](docs/screenshot.png)

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

[View the Live Demo Here](https://[YOUR-GITHUB-USERNAME].github.io/nepali-tts-studio/) 
*(Update this link once you publish via GitHub Pages)*

## 🛠️ Technical Stack

* **Frontend:** HTML5, Vanilla JavaScript
* **Styling:** Tailwind CSS (via CDN)
* **API:** Google Gemini API (`gemini-2
