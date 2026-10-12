# QuizMaster Pro — Interactive Quiz Platform

A polished, responsive, frontend-only quiz application built with HTML5, CSS3 and vanilla JavaScript. QuizMaster Pro turns knowledge assessment into a gamified experience with timed questions, XP, streaks, achievements and a personal progress dashboard.

## Project abstract

QuizMaster Pro is an interactive knowledge assessment platform where users can select a topic, choose a difficulty level and answer randomized multiple-choice questions against a timer. The application provides immediate feedback and explanations, calculates scores, rewards users with experience points, and stores performance locally so that progress is available on the same browser.

## Features

- Eight quiz categories: General Knowledge, Science & Nature, Technology, History & Culture, Geography, Sports, Entertainment and Web Development.
- Six randomized questions per attempt, selected from a category question bank.
- Easy, Medium and Hard difficulty levels with different timers and XP rewards.
- Randomized answer order, live progress indicator and countdown timer.
- Immediate correct/incorrect feedback with explanations.
- XP rewards, streak bonuses and level progression.
- Results summary with score, accuracy and answer review.
- Dashboard showing total XP, quizzes played, accuracy, best streak and category performance.
- Achievement badges and recent quiz history.
- Local browser persistence using `localStorage`.
- Responsive dark interface for desktop, tablet and mobile.

## Technology stack

- **HTML5** — semantic page structure and accessible controls.
- **CSS3** — responsive layout, visual design, transitions and animations.
- **Vanilla JavaScript** — question selection, quiz logic, scoring, timers, achievements and local persistence.

No framework, backend, database or build step is required.

## How to run

1. Download or clone this repository.
2. Keep `index.html`, `styles.css` and `script.js` in the same folder.
3. Open `index.html` in a modern web browser.

For a local development server, you can also run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```text
quizmaster-pro/
├── index.html
├── styles.css
├── script.js
└── README.md
```

## Data and privacy

Quiz progress is stored in the browser's `localStorage`. It is not sent to a server. Clearing site data or switching browsers/devices will reset or separate the saved progress.

## Academic project note

**Project title:** QuizMaster Pro – A Gamified Interactive Quiz and Knowledge Assessment Platform  
**Subject area:** Web Programming / Frontend Development  
**Core concepts demonstrated:** DOM manipulation, arrays and objects, event handling, timers, conditional logic, responsive UI design and browser storage.
