# Markdown Slides

A lightweight, zero-dependency browser application that turns Markdown text into styled 16:9 presentation slides with live preview and fullscreen presentation mode.

---

## Key Features

- **Live Preview:** Real-time slide rendering powered by `marked.js`.
- **Slide Separation:** Simply separate slides using `---` dividers.
- **Aspect Ratio Locking:** Slides maintain a crisp, scalable 16:9 ratio across all screen sizes.
- **Responsive Fluid Typography:** Text scales dynamically using CSS Container Query Units (`cqw`), ensuring slides look consistent regardless of display size.
- **Fullscreen Presentation Mode:** Dedicated overlay supporting browser Fullscreen API (`F11`).
- **Deck Management:** Create, rename, switch, and delete multiple presentation decks.
- **Local Persistence:** Automatic saving and deck management powered by browser `localStorage`.
- **Keyboard Shortcuts:** Built-in shortcuts for rapid slide navigation and saving.
- **Dark/Light Theme:** Built-in auto-detection for dark and light system themes.

---

## Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Ctrl` + `S` / `Cmd` + `S` | Save current presentation deck |
| `←` (Left Arrow) | Navigate to previous slide |
| `→` (Right Arrow) | Navigate to next slide |
| `F11` | Toggle Fullscreen Presentation Mode |

---

## Getting Started

### Prerequisites

No build tools, bundlers, or local web servers are required. The application runs natively in any modern web browser with an internet connection (used to load the `marked.js` CDN).

### Running the App

1. Download or clone the HTML file to your local computer.
2. Double-click `index.html` (or open it in any modern browser).
3. Start editing your slides in the editor pane on the left!

---

## How to Write Slides

Write standard Markdown in the text editor. Use three hyphens (`---`) on a line by itself to create a slide break.

### Example Deck

```markdown
# Title Slide
## Presentation Subtitle

Created with Markdown Slides

---

# Features
- Easy syntax
- Fast live preview
- Standalone HTML file

---

# Code Snippet

```javascript
console.log("Hello, Slides!");
