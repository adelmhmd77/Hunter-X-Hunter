# HUNTER × HUNTER — The Last Mission

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-CDN-06B6D4?logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-222?logo=github)

A dark, animated, single-page fan website dedicated to the anime **Hunter × Hunter**.

<img width="1828" height="952" alt="image" src="https://github.com/user-attachments/assets/aa1e3dac-c0cb-44fc-b76b-e475b3a07548" />

---

## Overview

**HUNTER × HUNTER — The Last Mission** is a static, front-end-only landing page that introduces the Hunter × Hunter series. It covers the story, the main characters, the six story arcs, a selection of featured episodes, and the Nen power system. The page has a neon-cyan and crimson theme, scroll-reveal animations, and a glowing Nen-style cursor.

This is a fan-made showcase project and is not an official website.

## Features

- Fixed navigation bar with a desktop menu and a mobile hamburger menu (JavaScript toggle)
- Animated hero section with the series title, tagline, genre/rating pills, a 9.0 / 10 MyAnimeList score and call-to-action buttons
- **Story** section with key series facts: 148 episodes, 6 major arcs, 2011 remake, 9.0 MAL score, and Madhouse as the studio
- **Characters** section with cards for Gon, Killua, Kurapika and Leorio, plus profiles for Hisoka, Meruem and Chrollo Lucilfer
- **Story Arcs** section covering all six arcs with episode ranges:

  | # | Arc | Episodes |
  |---|-----|----------|
  | 01 | Hunter Exam | 1–21 |
  | 02 | Zoldyck Family | 22–26 |
  | 03 | Heavens Arena | 27–36 |
  | 04 | Yorknew City | 37–58 |
  | 05 | Greed Island | 59–75 |
  | 06 | Chimera Ant | 76–136 |

- **Featured Episodes** list (episodes 1, 36, 116, 131 and 148)
- **Nen System** section explaining the six Nen types: Enhancement, Transmutation, Conjuration, Emission, Manipulation and Specialization
- Quote banner featuring a line from Ging Freecss
- Visual effects: floating particles, scanlines, spinning rings, glow and flicker animations, a custom scrollbar and scroll-triggered reveal animations
- Responsive layout using Tailwind CSS breakpoints

## Technologies

| Technology | Usage |
|------------|-------|
| HTML5 | Page structure |
| Tailwind CSS | Styling, loaded via the CDN script (`cdn.tailwindcss.com`) with an inline custom theme config |
| Custom CSS | Animations and effects in an inline `<style>` block |
| Vanilla JavaScript | Mobile menu, cursor glow, scroll reveal and particle generation |
| Font Awesome 6.0.0 | Icons, loaded from cdnjs |
| Google Fonts | Cinzel Decorative, Cinzel and Rajdhani |
| GitHub Pages | Hosting |

No build tools, package manager or frameworks are used.

## Getting Started

### Prerequisites

- A modern web browser
- An internet connection, since Tailwind CSS, Font Awesome and Google Fonts are loaded from CDNs

### Installation

```bash
git clone https://github.com/adelmhmd77/Hunter-X-Hunter.git
cd Hunter-X-Hunter
```

### Usage

Open `index.html` in your browser, or visit the [live demo](https://adelmhmd77.github.io/Hunter-X-Hunter/).

To customize the page, edit `index.html` directly. All markup, styles and scripts are in that single file.

## Project Structure

```text
Hunter-X-Hunter/
├── index.html
└── README.md
```

## Live Demo

[View the live website](https://adelmhmd77.github.io/Hunter-X-Hunter/)

## Repository

[GitHub Repository](https://github.com/adelmhmd77/Hunter-X-Hunter)

## License

Not
