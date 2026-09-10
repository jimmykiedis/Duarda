# 💌 Polaroid Memories – Declare Your Love in Style!

<p align="center">
  <a href="https://jimmykiedis.github.io/Duarda/">
    <img src="https://img.shields.io/badge/❤️%20Live%20Demo-FF4B4B?style=for-the-badge" alt="Live Demo">
  </a>
  <br>
  <em>Click the image to access the live demo.</em>
</p>

---

This is a mini-project built with **HTML, CSS, and JavaScript**, created to **express your love in a special way**! 🥰

You can display photos in a *Polaroid-style* layout, add background music 🎵, and include messages or memories that marked your story together. Everything comes together in a nostalgic and unique experience! 📸✨

---

## 🎯 Objective

This project was created with love ❤️ as an **interactive and emotional gift**, making it ideal for:

- Special occasions such as anniversaries, weddings, Valentine's Day, and more.
- Dating or marriage proposals.
- Spontaneous declarations of love.
- Creative gifts for someone special.

---

## ✨ Features

- 📸 Photo display in a Polaroid-style layout.
- ✨ Image reveal effect when clicking the photo.
- ⬅️ ➡️ Navigation buttons to move between photos.
- 🎵 Optional background music.
- 💌 Fully customizable messages and memories.
- ❤️ Decorative animations and visual effects.

---

## 🛠 How to Use the Repository

### 📥 1. Clone the Repository

Clone or download the repository and open the project folder in the terminal.

```bash
git clone https://github.com/jimmykiedis/Duarda.git
cd Duarda
```

### 🖼️ 2. Add Your Images

Place your images inside the `contents/` folder.

For example:

```text
contents/
├── roll1.png
├── roll2.png
└── roll3.png
```

### 🎵 3. Add Background Music

Optionally, add a background song to the HTML using the `<audio>` element.

```html
<audio controls>
  <source src="contents/music.mp3" type="audio/mpeg">
</audio>
```

### ✏️ 4. Customize the Content

Customize the messages, memories, images, and visual elements according to your needs.

You can also add text bubbles, captions, messages below the photos, and other personalized elements.

### ▶️ 5. Run the Project

Open `index.html` in your browser and enjoy the experience. ✨

---

## 🏗️ Implementation Strategy

The application is mainly structured with **HTML, CSS, and JavaScript**, using conventional DOM elements to build and control the interactive experience.

### Interface (HTML/CSS)

Responsible for the structure and presentation of the page elements, including:

- Polaroid-style photo gallery.
- Image and message display.
- Navigation buttons between photos.
- Music playback and pause controls.
- Animations and visual effects.
- Decorative elements such as floating hearts.

### Logic and Interaction (JavaScript)

JavaScript controls the application's dynamic behavior, including:

- Loading images from a `JSON` file.
- Loading messages from a `TXT` file.
- Synchronizing each image with its corresponding message.
- Navigating between photos using buttons and drag gestures.
- Supporting mouse and touch interactions.
- Switching between the front and back of the Polaroid.
- Controlling background music playback.
- Dynamically creating hearts and visual effects.
- Updating page content without requiring a page reload.

This approach keeps the application simple and organized by separating the **customizable content**, stored in external files, from the **logic responsible for interaction and presentation**.

---

## 🛠️ Technologies

- **HTML5** — Page structure and interface elements.
- **CSS3** — Styling, layout, animations, and visual effects for the Polaroid, hearts, and interactions.
- **JavaScript (Vanilla JS)** — Application logic, navigation, gestures, content loading, and audio control.
- **Fetch API** — Dynamic loading of images and messages from external files.
- **JSON** — Storage and organization of the image list.
- **HTMLAudioElement** — Background music playback and control.
- **DOM API** — Dynamic manipulation of HTML elements and creation of decorative elements.
- **Touch Events API** — Touch interaction support for mobile devices.

---

## 💡 Suggested Structure

```text
/
├── index.html
├── style.css
├── script.js
└── contents/
    ├── roll1.png
    ├── roll2.png
    └── music.mp3
```

---

## ❤️ Special Tip

> If love were code, this project would be an unforgettable commit in the repository of the heart. 💾💘

---

## 📄 License

Feel free to use, edit, and share! Spread love wherever you go. 🫡
