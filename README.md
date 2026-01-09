🪨 Slate - Daily Word Puzzle Game

A daily word puzzle game where you complete 8 five-letter words using the fewest consonant reveals possible.

## 🎮 How to Play

1. **Vowels are pre-filled** - Each word shows its vowels (A, E, I, O, U) already in place
2. **Fill in the consonants** - You have two ways:
   - **Click a square** → Opens a modal to select a specific consonant for that spot
   - **Click a bottom consonant button** → Reveals that letter everywhere in the grid (+1 point)
3. **Complete all 8 words** - Each word scores the current consonant count when completed
4. **Stay under 50 points** - Exceeding the point limit ends the game

## 📊 Scoring

- **Consonant Count**: Increases by 1 each time you use a global reveal (bottom buttons)
- **Word Score**: When you complete a word, it scores the current consonant count
- **Total Score**: Sum of all word scores
- **Point Limit**: 50 (game ends if exceeded or mathematically impossible to win)

### Rating System

| Score | Rating |
|-------|--------|
| 0 | 🏆 PERFECT! |
| 1-8 | ⭐⭐⭐ MASTER |
| 9-16 | ⭐⭐ EXPERT |
| 17-24 | ⭐ SKILLED |
| 25-32 | ✨ PROFICIENT |
| 33-40 | 👍 COMPETENT |
| 41-48 | 📚 DEVELOPING |
| 49 | ✓ COMPLETED |
| 50+ | 💀 POINTS EXCEEDED |

## 🎯 Difficulty Modes

### Easy Mode (Default)
When you complete a word by filling individual squares, all consonants from that word automatically appear in other incomplete words **for FREE** (no point increase). Great for learning!

### Hard Mode
No free reveals. Every consonant action counts. For experienced players seeking the best scores.

## ⌨️ Keyboard Shortcuts

| Context | Key | Action |
|---------|-----|--------|
| Modal open | A-Z | Fill selected square with consonant |
| No modal open | A-Z | Global reveal (with confirmation if enabled) |
| Confirmation modal | Enter | Confirm reveal |
| Any modal | Escape | Close/cancel |

## ⚙️ Settings

### Confirm Keyboard Reveals (Default: ON)
When enabled, typing a consonant key with no modal open will show a confirmation dialog before revealing. This prevents accidental point usage from stray keypresses.

**Note**: Clicking the bottom consonant buttons directly does NOT show confirmation (intentional clicks are trusted).

## 📱 Features

- **Daily Puzzles**: New words every day at midnight (seeded random for consistency)
- **Progress Tracking**: See your score, consonant count, and words completed
- **Share Results**: Copy your results with emoji grid to share with friends
- **Mobile Friendly**: Responsive design works on all screen sizes
- **Dark Theme**: Easy on the eyes chalkboard aesthetic

## 📤 Share Format
```
🪨 Slate #1 🟢 Easy

🟩🟨🟩🟩🟩
🟩🟩🟨🟩🟩
🟩🟨🟩🟩🟩
🟩🟩🟩🟨🟩
🟩🟨🟩🟩🟩
🟩🟩🟨🟩🟩
🟩🟨🟩🟩🟩
🟩🟩🟩🟨🟩

🎯 Score: 12 ⭐⭐
📊 Consonants: 8

https://slate.game
```

- 🟩 Green = Consonant position
- 🟨 Yellow = Vowel position
- 🟥 Red = Failed word (on loss)
- 🟢 Easy mode / 🔴 Hard mode

## 🛠️ Technical Details

- **Single HTML file**: No build process required
- **No dependencies**: Pure HTML, CSS, and JavaScript
- **LocalStorage**: Saves difficulty mode and confirmation setting preferences
- **2000 word database**: Curated list of common 5-letter words with vowels

## 📁 Files

- `slate.html` - Complete game (single file, ready to deploy)
- `README.md` - This documentation
- `CHANGELOG.md` - Version history

## 🚀 Deployment

Simply upload `slate.html` to any web server. No build step required.

For the share feature to use native mobile sharing (Messages, Mail, etc.), the site must be served over HTTPS.

## 📜 Version

**v1.2** - January 2026

---

Created with ❤️ as a daily word puzzle challenge.
