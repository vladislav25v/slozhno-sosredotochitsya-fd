# Hard to Focus — Practicum Project

A responsive single‑page website that explores the feeling of being overwhelmed and distracted in the digital age.  
The project was built as part of a **frontend practicum** and demonstrates confident use of modern **HTML5, CSS3** adaptive techniques.

---

## ✨ Key Features

| Feature                                    | Summary                                                                                                                                                                       |
| ------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Responsive Layout**                      | Mobile‑first design that scales gracefully from 375 px to 1024 px and wider using `clamp()`, Flexbox and CSS Grid.                                                            |
| **Automatic & Manual Dark / Light Themes** | Uses the `prefers‑color‑scheme` media query and a custom toggle written in JS to persist the user’s choice in `localStorage`.                                                 |
| **Component‑Driven CSS**                   | BEM‑style class naming, CSS Custom Properties, utility classes and separate theme layers (`globals.css`, `variables.css`, `utils.css`, `style.css`, `dark.css`, `light.css`). |
| **Semantic, Accessible HTML**              | Proper landmark elements (`header`, `main`, `section`, etc.), alt text for images, scalable typography and `lang="ru"` for screen readers.                                    |

---

## 🗂 Project Structure

```
slozhno-sosredotochitsya-fd/
├── index.html
├── styles/
│   ├── globals.css
│   ├── variables.css
│   ├── utils.css
│   ├── style.css
│   ├── dark.css
│   └── light.css
├── scripts/
│   └── script.js
├── images/
│   ├── *.png / *.jpg / *.svg
│   └── favicon files
├── fonts/
│   └── *.woff2
└── .git/ (version‑control data)
```

---

## 🛠 Built With

- **HTML5**
- **CSS3**
  - Flexbox & CSS Grid
  - `clamp()`, `min()`, `max()` fluid sizing
  - Custom properties (CSS variables)
  - `prefers-color-scheme` media query
  - JavaScript (ES6+)
  - DOM API
- **Git**

---

## 🙋‍♀️ Author

**Vlad** — [GitHub](https://github.com/vladislav25v) · [Telegram](https://t.me/@badabuduz)

Feel free to open an issue or submit a pull request if you have suggestions for improvements!
