# FocusFlow

A responsive Pomodoro productivity app built with HTML, CSS, and Vanilla JavaScript with no frameworks or external dependencies.

![FocusFlow Preview](https://img.shields.io/badge/status-live-brightgreen) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JS](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Features

### ⏱ Pomodoro Timer
- **Customizable Durations:** Configure Focus, Short Break, and Long Break durations with no 25-minute restriction.
- **Visual Progress Ring:** SVG circular progress indicator displaying green during Focus sessions and blue during Breaks.
- **Automated Workflow:** Automatically switches from Focus → Short Break → Long Break every 4 sessions.
- **Full Controls:** Start, pause, reset, and skip options.
- **Audio Alerts:** Authentic bell chime synthesized using the Web Audio API with inharmonic partials for natural resonance.
- **Browser Notifications:** Receive desktop notifications upon session completion.

### ✅ Task Manager
- Add, complete, and delete tasks.
- Select a active task to display under "Currently Working On".
- Track pomodoros completed per task.
- Persistent state using `localStorage`.

### 🌙 Dark / Light Mode
- Header toggle button to manually switch themes.
- Respects system preference via `prefers-color-scheme`.
- Theme selection saved in `localStorage`.

### 📊 Daily Stats
- Track total pomodoros completed today.
- Track total focus minutes.
- Automatically resets statistics at midnight.

## Technologies Used

- **HTML5:** Semantic layout and ARIA accessibility features.
- **CSS3:** Custom properties (variables), CSS Grid, Flexbox, SVG animations, and light/dark theme styling.
- **Vanilla JavaScript:** Web Audio API, DOM manipulation, `setInterval`, and `localStorage`.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/imaakarsh/FocusFlow.git
   ```
2. Open `index.html` in any modern web browser (no build step required).

## Usage

1. **Configure Timer:** Click the ⚙ gear icon to customize Focus and Break session durations.
2. **Add Tasks:** Type a task description in the right panel and press Enter or click **Add**.
3. **Select Active Task:** Click a task to set it as active.
4. **Run Timer:** Click **Start**. An audio chime will sound when the session ends.
5. **Track Progress:** View pomodoros completed per task and overall metrics in the footer.

## Color Theme

| Element | Dark Mode | Light Mode |
|---|---|---|
| Background | `#0D0D0F` | `#FFF8F2` |
| Card | `#161618` | `#FFFFFF` |
| Accent | `#F97316` (Orange) | `#EA580C` |
| Focus Ring | `#22C55E` (Green) | `#16A34A` |
| Break Ring | `#3B82F6` (Blue) | `#3B82F6` |

## Project Structure

```text
FocusFlow/
├── index.html    # App structure & layout
├── style.css     # All styling, themes, animations
└── script.js     # Timer logic, tasks, audio, localStorage
```

## Credits

Created by **Aakarsh Dev**.