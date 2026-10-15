# 🐍 Ghost Snake Game

A classic Snake game built with plain HTML, CSS and JavaScript.

## Features

- Smooth canvas-based gameplay
- Snake gets faster as you eat
- Score and best score (saved in your browser using `localStorage`)
- Pause / resume
- Keyboard controls and mobile support (swipe + on-screen buttons)
- Responsive layout

## How to Run

**Option 1: Open directly**

1. Download or clone this repo
2. Double-click `snake.html`

**Option 2: Clone with Git**

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

Then open `snake.html` in any browser.

## Controls

 Action          Keys                     
 Move up        `↑` or `W`               
 Move down      `↓` or `S`               
 Move left      `←` or `A`               
 Move right     `→` or `D`               
 Pause/Resume   `Space`                  
 Start/Restart  `Enter` or `Space`       

On mobile, swipe on the board or use the on-screen arrow buttons.

## Rules

- Eat the red food to grow and score a point
- Don't hit the walls
- Don't hit your own body

## Play Online (GitHub Pages)

1. Go to your repo → **Settings** → **Pages**
2. Under **Source**, select the `main` branch and `/ (root)`, then Save
3. After a minute, play at:
   `https://<your-username>.github.io/<your-repo>/snake.html`

## Project Structure

```
.
├── snake.html   # The complete game (HTML + CSS + JS)
├── README.md


## Ideas for Improvement

- Difficulty levels (slow / normal / fast)
- Wrap-around walls mode
- Sound effects
- Obstacles or power-ups
- Global leaderboard


