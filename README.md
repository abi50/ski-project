# 🎿 Ski School Website – Web Design Project

This is a full static website designed as part of a web design project.  
It presents a ski school using modern HTML, CSS, images, videos, and Hebrew fonts.

---

## 📁 Project Structure

```
ski-project/
│
├── css/               # All CSS styling files
│   ├── home.css
│   ├── information.css
│   └── skischool.css
│
├── img/               # Images, logos, icons
│   └── ... (over 100 images)
│
├── pages/             # Main HTML pages
│   ├── home.html
│   ├── information.html
│   └── skischool.html
│
├── video/             # Embedded MP4 videos
│   ├── video1.mp4
│   ├── video2.mp4
│   └── video3.mp4
│
├── פונטים/           # Hebrew fonts (Secular One + license files)
│   ├── SecularOne-Regular.ttf
│   ├── OFL.txt
│   └── README.txt
│
└── README.md          # This file
```

---

## 🎨 What the Website Includes

- Home page with modern layout and header
- About page with FAQ and information
- Ski school course details and pricing
- Hebrew text styling with custom font
- Embedded videos and responsive design

---

## 🔤 Font Usage – Secular One

The site uses a Hebrew font named **Secular One**, located under the `פונטים/` directory.

To make the font work without installation:
- Each CSS file includes a `@font-face` rule like this:

```css
@font-face {
  font-family: 'Secular One';
  src: url('../פונטים/SecularOne-Regular.ttf') format('truetype');
}
```

This ensures the font loads automatically from the local folder, even if it’s not installed on the system.

---

## 🖥️ How to Run Locally

1. Open `pages/home.html` in your browser.
2. Make sure all folders (`css/`, `img/`, `video/`, `פונטים/`) are in the correct relative paths.
3. Navigate between pages using the site menu.

---

### 🌍 Live Demo

You can view the site here:  
➡️ [https://abi50.github.io/ski-project/](https://abi50.github.io/ski-project/)
---

## 👤 Project Author

**Abigail Berk**  
[GitHub](https://github.com/abi50)  
[Email](mailto:abigail506040@gmail.com)
