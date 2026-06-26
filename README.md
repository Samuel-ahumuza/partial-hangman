# partial-hangman
A word guessing game where partial letters are revealed and you fill in the blanks to complete the word.
# 🔤 LetterClue / Word Reveal Game

> A browser-based word-guessing game where partial letters are revealed and you fill in the blanks to complete the word.

---

## 📖 About

**LetterClue** is a reimagined Hangman experience. Instead of guessing completely blind, players are shown a partially revealed word — like `_ a _ _ m a _` — and must figure out the full word before running out of lives. It blends the classic tension of Hangman with the satisfying "aha!" moment of word recognition.

Built entirely in **one single HTML file** — no frameworks, no dependencies, no build tools.

---

## 🎮 How to Play

1. A word is chosen at random from a themed category (Animals, Space, Food, Music, etc.)
2. Some letters are pre-revealed as clues the rest are shown as blanks `_`
3. Use the on-screen keyboard (or your physical keyboard) to guess the missing letters
4. You have **6 lives** — each wrong guess costs one
5. Use the 💡 **Hint** button if you're stuck
6. Complete the word before the hangman is fully drawn to win points!

---

## ✨ Features

- 🧩 **Partial letter reveals** — random letters pre-filled as clues each round
- 🔊 **Sound effects** — chimes for correct guesses, buzzes for wrong ones, fanfare on win
- ❤️ **Lives system** — 6 chances with animated heart indicators
- 🏆 **Score tracker** — earn more points by using fewer guesses
- 💡 **Hint system** — one contextual hint per word
- 🎨 **Vintage paper aesthetic** — warm cream, burnt orange & charcoal ink design
- ⌨️ **Physical keyboard support** — just type your guesses on desktop
- 📱 **Fully responsive** — works on mobile, tablet, and desktop
- 🗂️ **40+ words** across 8 categories: Animals, Nature, Music, History, Space, Food, Places, Science & Tech

---

## 🚀 Getting Started

No installation needed. Just open the file in any modern browser.

```bash
# Clone the repo
git clone https://github.com/Samuel-ahumuza/partial-hangman

# Open the game
open hangman.html
```

Or simply **download `hangman.html`** and double-click it.

---

## 🗂️ Project Structure

```
letterclue/
│
├── hangman.html      # The entire game — HTML + CSS + JS in one file
└── README.md         # You're reading it
```

---

## 🛠️ Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Markup     | HTML5                             |
| Styling    | CSS3 (custom properties, animations, CSS Grid) |
| Logic      | Vanilla JavaScript (ES6+)         |
| Audio      | Web Audio API (no audio files needed) |
| Fonts      | Google Fonts — Bebas Neue, DM Mono, Outfit |

---

## 🎨 Design

The game uses a **vintage paper aesthetic** deliberately avoiding generic AI colour schemes (no purple gradients, no dark mode blues). The palette is built around:

- `#f5ede0` — warm cream paper background
- `#c0440a` — burnt orange accent
- `#3d2e1e` — deep charcoal ink
- `#2e7d4f` — forest green for correct guesses
- `#b32828` — deep red for wrong guesses

---

## 📝 Word Categories

| Category  | Examples                          |
|-----------|-----------------------------------|
| 🐾 Animals | Elephant, Chameleon, Platypus    |
| 🌋 Nature  | Volcano, Glacier, Avalanche      |
| 🎵 Music   | Saxophone, Trumpet, Violin       |
| 🏛️ History | Colosseum, Pyramid, Gladiator    |
| 🚀 Space   | Nebula, Asteroid, Black Hole     |
| 🍕 Food    | Croissant, Avocado, Pineapple    |
| 🏙️ Places  | Lighthouse, Stadium, Museum      |
| 🔬 Science | Microscope, Molecule, Algorithm  |

---

## 🤝 Contributing

Pull requests are welcome! Ideas for contribution:

- Add more word categories
- Add a difficulty selector (easy / medium / hard — fewer clue letters)
- Add a timer mode
- Add high score persistence via `localStorage`
- Add more sound variety

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

*Made with ☕ and one HTML file.*
