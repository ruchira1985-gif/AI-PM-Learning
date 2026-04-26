# Product Requirements Document (PRD) — Memory Game

## 1. Overview
A browser-based Memory (Concentration) card game built with pure HTML, CSS, and JavaScript. The game is designed to be accessible, responsive, and free of external dependencies.

## 2. Features
- Two grid sizes: 4x4 and 6x6
- Card flip animations
- Timer and move counter
- Star rating system based on performance
- Persistent best scores using local storage
- Keyboard controls for accessibility (Tab, Enter/Space)
- Responsive design for all device sizes
- ARIA attributes for accessibility

## 3. User Flow
1. User opens the game in a browser
2. User selects grid size (4x4 or 6x6)
3. User flips cards to find matching pairs
4. Game tracks moves and time
5. Game ends when all pairs are matched
6. User sees their score, time, and star rating
7. Best scores are saved locally

## 4. Technical Requirements
- Pure HTML, CSS, and JavaScript
- No external libraries or frameworks
- CSS Grid for layout
- Local storage for high scores
- ARIA and keyboard navigation for accessibility

## 5. Non-Functional Requirements
- Works on all modern browsers
- Fully responsive and mobile-friendly
- No network connection required after loading
