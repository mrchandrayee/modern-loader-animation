# Modern Loader Animation

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/modern-loader-animation/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A complete runnable recreation of the uploaded 21.37-second screen recording.

## Video content

The screen title is **Modern Loader Animation**. It shows five separate dark preview/code cards, each with a cyan glowing outline. The page background is near-black navy, with a glowing blue title and cyan accent bars beside each section heading.

The five loader names and visible CSS snippets, in the order shown:

### 1. Neon Ring Loader

```css
.ring-loader {
  width: 130px;
  height: 130px;
  border-radius: 50%;
  border: 8px solid transparent;
  border-top: 8px solid cyan;
  border-right: 8px solid magenta;
  animation: ringSpin 1s linear infinite;
}
```

### 2. Morphing Shape Loader

```css
.morph-loader {
  width: 100px;
  height: 100px;
  background: linear-gradient(cyan, magenta);
  animation: morph 2s infinite;
}
```

### 3. Liquid Wave Loader

```css
.liquid-loader {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  overflow: hidden;
  border: 4px solid cyan;
}
```

### 4. Orbit Dot Loader

```css
.dot {
  width: 22px;
  height: 22px;
  border-radius: 50%;
  animation: orbit 2s linear infinite;
}
```

### 5. Futuristic Bar Loader

```css
.bar {
  width: 18px;
  height: 120px;
  border-radius: 20px;
  animation: bars 1s infinite;
}
```

The visible code panels show the declarations above. The keyframe definitions and layout markup are not fully displayed in the recording, so the runnable project supplies reconstructed keyframes and layout around the transcribed declarations.

## Run

1. Extract the ZIP.
2. Open `index.html` in Chrome, Firefox, Safari, or Edge.
3. All five loaders animate automatically. No interaction is needed.

No packages, build tools, server, or external image assets are required.

## Files

- `index.html` — five preview panels and their visible CSS snippets
- `style.css` — full layout, neon panel styling, and all five animations
- `README.md` — video transcription and run instructions

## Source fidelity note

The five names and CSS declarations above were read from the visible code panels in the uploaded video. The rest of the CSS, keyframes, and page markup are a complete working reconstruction; they are not claimed to be the creator's exact hidden original source.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
