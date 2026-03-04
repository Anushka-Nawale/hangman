# 🎯 Hangman Game

> A classic Hangman word-guessing game built with **React** + **TypeScript** + **Vite**


🎬 Demo
https://github.com/user-attachments/assets/730dda7b-b60a-48b8-b151-4446e071e04f

## ✨ Features

- 🎲 **Random word generation** from a large English word list
- ⌨️ **Dual input support** — click on-screen keyboard or type on your physical keyboard
- 🖼️ **Animated Hangman figure** that draws progressively with each wrong guess
- 🔴 **Missed letters revealed in red** when you lose
- 🏆 **Win & lose detection** with instant feedback
- ♻️ **Press Enter** to reset and play a new round
- 📱 **Responsive layout** that works on all screen sizes

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| ⚛️ React 18 | UI & component logic |
| 🔷 TypeScript | Type safety |
| ⚡ Vite | Fast dev server & bundler |
| 🎨 CSS Modules | Scoped component styling |

---

## 📁 Project Structure

```
hangman/
├── src/
│   ├── components/
│   │   ├── HangmanDrawing.tsx   # SVG figure that draws with wrong guesses
│   │   ├── HangmanWord.tsx      # Word display with hidden/revealed letters
│   │   └── Keyboard.tsx         # On-screen A–Z keyboard
│   ├── wordList.json            # Large English word bank
│   ├── App.tsx                  # Main game logic & state
│   └── main.tsx                 # App entry point
├── .gitignore
├── package.json
├── tsconfig.json
└── vite.config.ts
```

---

## ⚙️ Getting Started

### Prerequisites
- Node.js ≥ 16
- npm or yarn

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/hangman.git

# 2. Navigate into the project
cd hangman

# 3. Install dependencies
npm install

# 4. Start the dev server
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 🎮 How to Play

1. A **random word** is chosen and shown as blank underscores
2. **Guess letters** by clicking the on-screen keyboard or pressing keys
3. Each **wrong guess** adds a body part to the Hangman figure
4. You have **6 attempts** before you lose
5. Guess all letters correctly to **win!**
6. Press **Enter** at any time to start a new game

---

## 🚢 Deployment

You can deploy this easily on **Vercel** or **Netlify**:

```bash
# Build for production
npm run build

# Preview the production build locally
npm run preview
```

Then drag the `dist/` folder into [Netlify Drop](https://app.netlify.com/drop) — done!





