# 🥁 Drum Kit Game

An interactive browser-based drum kit built with **HTML, CSS, and JavaScript**. Play different drum sounds by clicking the drum buttons or pressing the corresponding keys on your keyboard.

## ✨ Features

- 🥁 Seven playable drum sounds
- 🖱️ Play sounds by clicking the drum buttons
- ⌨️ Play sounds using keyboard controls
- 🎵 Individual audio files for each drum sound
- ✨ Visual button animation when a drum is played
- 🎨 CSS-based drum button styling with instrument images

## 🎹 Controls

| Key | Sound |
|---|---|
| **W** | Tom 1 |
| **A** | Tom 2 |
| **S** | Tom 3 |
| **D** | Tom 4 |
| **J** | Snare |
| **K** | Crash |
| **L** | Kick Bass |

You can also click any of the seven drum buttons directly.

## 🛠️ Technologies Used

- **HTML5** – page structure and drum buttons
- **CSS3** – layout, styling, instrument backgrounds, and button animation
- **JavaScript** – click/keyboard event handling, audio playback, and animation
- **HTML Audio API** – loading and playing the drum sound files

## ⚙️ How It Works

The JavaScript attaches click event listeners to all elements with the `.drum` class. When a button is clicked, its letter is used to select the corresponding drum sound.

A keyboard event listener also detects pressed keys. The `makeSound()` function maps each supported key to an audio file, while `buttonAnimation()` temporarily adds the `.pressed` class to provide visual feedback.

The project uses these sound mappings:

- `w` → `tom-1.mp3`
- `a` → `tom-2.mp3`
- `s` → `tom-3.mp3`
- `d` → `tom-4.mp3`
- `j` → `snare.mp3`
- `k` → `crash.mp3`
- `l` → `kick-bass.mp3`

## 📁 Project Structure

```text
drum-kit-game/
├── index.html
├── index.js
├── styles.css
├── images/
│   ├── tom1.png
│   ├── tom2.png
│   ├── tom3.png
│   ├── tom4.png
│   ├── snare.png
│   ├── crash.png
│   └── kick.png
└── sounds/
    ├── tom-1.mp3
    ├── tom-2.mp3
    ├── tom-3.mp3
    ├── tom-4.mp3
    ├── snare.mp3
    ├── crash.mp3
    └── kick-bass.mp3
```

## 🚀 Run Locally

1. Clone the repository:

```bash
git clone https://github.com/jothikapugaz/drum-kit-game.git
```

2. Open the project folder in VS Code.
3. Make sure the `images` and `sounds` folders are present.
4. Open `index.html` in a browser.
5. Click the drum buttons or use the **W, A, S, D, J, K, L** keys to play.

For development, you can also use the **Live Server** extension in VS Code.

## 📚 What I Practiced

This project helped me practice:

- JavaScript event listeners
- Handling mouse clicks and keyboard events
- DOM selection and manipulation
- JavaScript functions and switch statements
- Playing audio with JavaScript
- Adding and removing CSS classes dynamically
- Using `setTimeout()` for short visual animations
- Organizing a small interactive frontend project

## 🔮 Possible Improvements

Future versions could include:

- A volume control
- A recording and playback feature
- Custom drum-kit sounds
- A visual beat or rhythm indicator
- Score or rhythm challenges
- Improved responsive styling for different screen sizes

## 👩‍💻 Author

**Jothika P**

Computer Science & Engineering graduate | Aspiring Full-Stack Developer

GitHub: [@jothikapugaz](https://github.com/jothikapugaz)
