

###  README Preview

```markdown
#  Offline Flashcard Generator

> Transform raw study notes and definitions into interactive, 3D-flippable flashcards instantly — completely offline, private, and with zero dependencies.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![No Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen.svg)](#)
[![Privacy Friendly](https://img.shields.io/badge/Privacy-100%25%20Offline-blueviolet.svg)](#)

---

##  Overview
Creating flashcards manually is tedious. **Offline Flashcard Generator** is a lightweight, single-file web application that uses heuristic pattern extraction to parse raw study notes, definitions, and bullet points into an interactive flashcard deck.

Everything runs **100% client-side** inside your web browser. No servers, no signups, no API keys, and no network requests required.

---

##  Features
- ** Instant Card Extraction**: Converts unstructured notes into flashcards with one click.
- ** 100% Private & Offline**: Works completely without internet; your notes never leave your browser.
- ** Sleek Dark UI**: Built with modern CSS custom properties and smooth gradient accents.
- ** Realistic 3D Card Flip**: Realistic CSS `perspective` and `preserve-3d` animations.
- ** Responsive Design**: Works seamlessly on desktop, tablet, and mobile screens.
- ** Zero Dependencies**: Pure Vanilla HTML, CSS, and JavaScript. Just open `index.html`.

---

##  How the Parser Works

| Rule Type | Source Text Pattern | Generated Question | Generated Answer |
| :--- | :--- | :--- | :--- |
| **Key-Value Pair** | `RAM: Random Access Memory` | *What is RAM?* | `Random Access Memory` |
| **Definition Verbs** | `Mitochondria are the powerhouse of the cell.` | *What is Mitochondria?* | `Mitochondria are the powerhouse of the cell.` |
| **Cloze Fallback** | `Photosynthesis converts light into chemical energy.` | *Fill in the blank:<br>"_______ converts light into chemical energy."* | `Photosynthesis` |

---

##  Getting Started

### 1. Clone or Download
```bash
git clone https://github.com/your-username/offline-flashcard-generator.git
cd offline-flashcard-generator
```

### 2. Run It
Simply open `index.html` in any modern web browser.
```

---

### Project Files in Workspace

* [index.html](file:///C:/Users/USER/.gemini/antigravity/scratch/flashcards/index.html) — The application code
* [README.md](file:///C:/Users/USER/.gemini/antigravity/scratch/flashcards/README.md) — GitHub documentation with badges, parser table, and setup guide
* [LICENSE](file:///C:/Users/USER/.gemini/antigravity/scratch/flashcards/LICENSE) — MIT License file
