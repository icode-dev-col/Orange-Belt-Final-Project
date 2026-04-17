# Magical Forest Project – Team Instructions

Welcome to the Orange Belt Final Project!

We are building a **multi-page fantasy website** where users explore a magical forest and choose between:
- 🐉 Dragon
- 🦄 Unicorn
- 🧝 Elf

Each creature has its own mini-website with:
- Gallery (Home)
- Mini-game
- Information page

---

# Team Roles

Each person has a PRIMARY responsibility, but everyone will use HTML, CSS, and JavaScript.

### 🐉 Aiden – UI Lead
- Design layouts for pages
- Structure HTML for all creature pages
- Ensure navigation links work properly
- Make pages user-friendly

---

### 🎮 Ethan – Game Lead
- Build mini-games for each creature
- Add interactivity using JavaScript
- Handle game logic (score, clicks, etc.)
- Test games to make sure they work

---

### 🎨 Maya – Styling & Animation Lead
- Add CSS styling to all pages
- Implement colors, fonts, and themes
- Add animations (hover effects, transitions, particles)
- Maintain the “Lord of the Rings” fantasy theme

---

### 👩‍🏫 Ms. N – Integration & Homepage Lead
- Build and manage the main forest homepage (`index.html`)
- Connect all pages together
- Fix bugs and ensure everything works
- Final review before publishing

---

# Project Rules (VERY IMPORTANT)

## 🚨 Rule 1: Work ONLY in your assigned area

- Aiden → UI/layout
- Ethan → game files
- Maya → CSS & animations

Do NOT randomly edit other people’s files.

---

## 🚨 Rule 2: Folder Ownership

Each creature folder belongs to the team:

- `/dragon/` : AIDEN
- `/elf/` : ETHAN
- `/unicorn/` : MAYA

Only edit files inside your assigned section unless told otherwise.

---

## 🚨 Rule 3: Always PULL before starting

Before you begin coding:
1. Open GitHub Desktop
2. Click **Pull Origin**

This prevents overwriting other people’s work.

---

## 🚨 Rule 4: Commit your work

Every time you make progress:

1. Write a clear message
2. Click **Commit**

### ✅ Good commit messages:
- "Added dragon gallery layout"
- "Created unicorn game logic"
- "Styled elf info page"

### ❌ Bad commit messages:
- "update"
- "stuff"
- "idk"

---

## 🚨 Rule 5: Push your changes

After committing:
- Click **Push Origin**

This uploads your work to GitHub.

---

# Website Structure

Each creature must have:

## Gallery Page (`index.html`)
- Images
- Title
- Description

## Game Page (`game.html`)
- Interactive mini-game
- Buttons / clicks

## Info Page (`info.html`)
- Facts about the creature
- Headings + paragraphs

---

# Navigation Rules

Every page must include:

- Link to Home page (main forest)
- Links between creature pages

Example:

```html
<a href="../index.html">Back to Forest</a>
