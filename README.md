# The Magical Forest: Orange Belt Project

Welcome to the **Magical Forest**, an immersive, multi-page fantasy-themed website inspired by the aesthetics of Lord of the Rings. This project was built by the **Orange Belt Team** as a showcase of advanced HTML, CSS, and JavaScript skills, along with interactive web design principles.

Our site is live at https://icode-dev-col.github.io/Orange-Belt-Final-Project/

---

## The Fellowship of the Orange Belt

Our coding fellowship consists of:
* **Ms. N** - Grandmaster Instructor
* **AA** - Dragon Tamer
* **Maya** - Elven Ranger
* **Ethan** - Knight of the Realm

> **Note to the Team:** Check out `team.html` to update your avatars and link your own personal portfolio websites!

---

## Technologies Used

- **HTML5**: Used for structuring the content and creating a robust, multi-page architecture.
- **CSS3 (Vanilla)**: Used for responsive layouts (CSS Grid, Flexbox), custom theming, and complex visual effects.
- **Vanilla JavaScript (ES6)**: Used to add logic to our interactive mini-games and handle browser audio playback.

---

## Key Concepts & Learning Outcomes

This project is a perfect sandbox for exploring several intermediate web development concepts:

### 1. Multi-Page Architecture & Routing
Instead of a single scrolling page, this site is broken into modular folders (`/dragon`, `/unicorn`, `/elf`). We used **Relative Linking** (like `href="../index.html"`) to allow users to navigate deep into a folder and cleanly back out to the home page, simulating a large-scale website.

### 2. Modern CSS Features
* **CSS Variables (`:root`)**: We defined variables like `--gold` and `--bg-dark` at the highest level. This allowed us to easily maintain a consistent "Dark Fantasy" color palette across multiple style rules without hardcoding colors repeatedly.
* **Glassmorphism**: By using `backdrop-filter: blur(10px)` combined with semi-transparent RGBA backgrounds, we created the beautiful frosted-glass navigation bars that let the forest background shine through dynamically.
* **CSS Animations & Keyframes**: We used `@keyframes` to create the floating firefly particles (`float`), the continuous slow drift of the forest mist (`drift`), and the smooth page-load transitions, making the website feel alive without heavily relying on JavaScript animation libraries.

### 3. DOM Manipulation & Event Handling (JavaScript)
Each creature features an interactive mini-game utilizing basic DOM (Document Object Model) manipulation:
* **Event Listeners**: Tracking when a user `click`s a button or clicks an area on the screen.
* **Dynamic Node Creation**: In the Dragon game, when you offer gold, JavaScript uses `document.createElement('div')` to spawn gem emojis dynamically on the screen based on the user's mouse coordinates (`e.clientX`, `e.clientY`) and then removes them with `setTimeout` to prevent browser lag.
* **State Management**: Using simple JavaScript variables like `score` and `hits` to keep track of the game state and immediately updating the HTML text via `innerText` to provide instant feedback.

### 4. Interactive Media Handling
Browsers enforce strict "autoplay policies" that prevent audio from playing automatically to save users from annoying sudden noises. We circumvented this properly by building an "Enter the Realm" overlay prompt. When the user clicks the button, it satisfies the browser's requirement for "user interaction," allowing our JavaScript to safely trigger the `<audio>` tag's playback method (`forestAudio.play()`) and fade out the overlay text.

---

## Project Structure

```text
Orange belt project/
├── index.html                # Main entry point (Magical Forest Home)
├── team.html                 # Fellowship / team page
├── README.md                 # Project overview and documentation

├── css/
│   └── style.css             # Global stylesheet

├── images/                   # Fantasy assets
│   ├── forest.png
│   ├── dragon.png
│   ├── elf.png
│   └── unicorn.png

├── dragon/                   # Dragon Hub
│   ├── index.html            # Gallery
│   ├── info.html             # Lore
│   └── game.html             # "Feed the Dragon" Mini-game

├── elf/                      # Elf Hub
│   ├── index.html
│   ├── info.html
│   └── game.html             # "Archery Practice" Mini-game

├── unicorn/                  # Unicorn Hub
│   ├── index.html
│   ├── info.html
│   └── game.html             # "Reveal the Magic" Mini-game

├── instructions/             # Team roles & guidance (learning docs)
│   ├── Instructions.MD       # Overall project instructions
│   ├── Aiden.MD              # UI Lead (Front-End Architect)
│   ├── Ethan.MD              # Game Lead (Interaction Engineer)
│   ├── Maya.MD               # Styling & Animation Lead
│   └── instructor.md         # Integration & project management guide
```

---

## **Team Expectations & Final Presentation**

Throughout this project, each team member is expected to take ownership of their role and actively contribute to the development of the website.

### Expectations

* Keep track of your progress and updates during development
* Be familiar with the tools and concepts used in your section
* Write clear and meaningful commit messages when pushing code
* Test your work regularly to ensure everything functions correctly
* Collaborate with your teammates to maintain consistency across the website

---

### **Understanding Over Just Building**

Students are expected to not only build their components but also understand:

* How their code works
* Why certain tools or techniques were used
* How their section connects to the rest of the project

---

### **Final Presentation**

During the final class, each team member will present their work.

Each student should be prepared to explain:

* Their role in the project
* The features they built
* The tools and technologies they used (HTML, CSS, JavaScript, GitHub, etc.)
* How their code works (at a conceptual level)
* Any challenges they faced and how they solved them

---

### **Goal of the Presentation**

The goal is to demonstrate:

* Technical understanding
* Problem-solving skills
* Clear communication of ideas

This ensures that students are not only building projects, but also developing the ability to **explain and present their work like real developers**.
