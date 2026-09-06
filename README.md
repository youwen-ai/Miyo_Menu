# Asian Bistro Bilingual Waitstaff & Audio Menu Guide

An interactive, bilingual (English/Chinese) digital training menu designed to help restaurant waitstaff master dish names, pronunciations, and descriptions.

---

## Features

* **Click-to-Pronounce Audio:** Uses the browser-native Web Speech API (`window.speechSynthesis`) to provide natural US English pronunciation for dish names and descriptions[cite: 1, 2].
* **Bilingual Layout:** 1:1 English and Chinese dish names, ingredient breakdowns, and service notes[cite: 1, 2].
* **Cross-Platform Compatibility:** Runs directly in modern desktop and mobile browsers (Windows 11, iOS Safari, Chrome, Edge)[cite: 1, 2].
* **Targeted Phonetic Tuning:** Includes a lightweight phonetic dictionary (`PHONETIC_MAP`) for French wines, tricky loanwords, and homographs[cite: 2].
* **Offline-Friendly Asset Structure:** Local `images/` directory with automatic graceful fallback if an image is missing[cite: 1, 2].

---

## Repository Structure

```text
├── index.html        # Main interactive menu guide and audio engine
├── README.md         # Project overview and setup instructions
└── images/           # Dish, drink, and menu photos (e.g., edamame.jpg)
