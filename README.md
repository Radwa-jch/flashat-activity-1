# 🌙 فوازير رمضان البرمجية — Ramadan Riddles

> A fun, interactive Ramadan-themed riddle wheel — no install required, just open and play!

A single-page Arabic web activity built for Ramadan. Spin the colorful wheel and get a random riddle — ranging from classic Arabic riddles to programming trivia. Type your answer, get instant feedback, and the wheel spins again automatically!

---

## ✨ Features

- **Spin-the-wheel mechanic** — A CSS conic-gradient wheel with smooth spin animation selects a random question each round
- **20 riddles** — A mix of traditional Arabic riddles and programming questions (HTML, Python, Java, Swift, boolean types, loops, and more)
- **Instant feedback** — The page turns green for a correct answer, red for a wrong one
- **Auto-advance** — After each answer, the wheel spins again automatically after 2 seconds
- **Ramadan theming** — Moon, lantern, and mosque decorative elements with a festive gradient background
- **Fully in Arabic** — RTL-friendly layout with Arabic content throughout
- **Responsive** — Works on mobile and desktop
- **Zero dependencies** — Pure HTML, CSS, and vanilla JavaScript — no frameworks, no build step

---

## 🚀 How to Use

No installation needed. Just open the file in any browser:

```bash
# Clone the repo
git clone https://github.com/Radwa-jch/Riddles.git
cd Riddles

# Open in browser
open page.html
# or double-click page.html in your file explorer
```

That's it — no server, no packages, no setup.

---

## 🎮 How to Play

1. Click **"اختر سؤال عشوائي"** (Choose a random question) to spin the wheel
2. Wait for the wheel to stop — your riddle appears below it
3. Type your answer in the input field
4. Click **"تم"** (Done) to check your answer
5. The page flashes green ✅ or red ❌, then automatically spins again

---

## 📂 File Structure

```
Riddles/
└── page.html    # The entire app — HTML, CSS, and JS in one file
```

---

## 🧩 Riddle Categories

**Classic Arabic Riddles (10):**
Traditional riddles about everyday objects like lamps, books, clouds, combs, trees, and the moon.

**Programming Riddles (10):**
- What language is used to build web pages?
- What data type stores text?
- What Android app development language is commonly used?
- What's the comment symbol in Python?
- What does HTML stand for?
- How do you display output on screen?
- What data type holds only true or false?
- What language is used for iOS apps?
- What is a loop in programming?
- What beginner-friendly language is known for its simplicity?

---

## 🛠️ Customization

To add your own riddles, edit the `questions` and `answers` arrays in the `<script>` section of `page.html`:

```javascript
const questions = [
  "Your riddle here?",
  // ...
];

const answers = [
  "youranswer",  // lowercase, no diacritics
  // ...
];
```

Make sure each question at index `i` has its answer at the same index `i` in the answers array.

---

## 🌐 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure and content |
| CSS3 | Animations, conic gradient wheel, responsive layout |
| Vanilla JavaScript | Wheel spin logic, answer checking, auto-advance |

---

## 📄 License

Open source — use it, remix it, share it. Ramadan Kareem! 🌙
