# Web Techniques Lab

An interactive showcase of my **Web Techniques (2417MJCT101)** practical assignments for **F.Y. M.Sc. (IT)** at MAEER's MIT Arts, Commerce and Science College, Alandi (D), Pune.

Instead of a plain list of files, the repository includes a single-page website (`index.html`) that works like a video library. Every assignment program is a card. Open a card to run the program live, switch between desktop, tablet and phone sizes, and read its full source code.

**Live website:** https://your-project.vercel.app *(replace with your Vercel link)*

---

## What is inside

| Assignment | Topic | Marks | Programs |
| :--- | :--- | :---: | :---: |
| Assignment 1 | HTML5, Bootstrap and JavaScript | 25 | 13 |
| Assignment 2 | DOM, jQuery and JSON | 25 | 16 |

Total: **29 live programs** across **5 syllabus units**, plus the written theory answers for both assignments.

---

## Assignment 1: HTML5, Bootstrap and JavaScript

### Q1. HTML5 and Bootstrap (12 marks)

| File | Question | Marks |
| :--- | :--- | :---: |
| `Q1-A1.html` | Semantic elements with `div` and `span` | 2 |
| `Q1-A2.html` | Images with alt text, `srcset` and `picture` | 2 |
| `Q1-A3.html` | Table with `thead`, `tbody`, `tfoot`, `rowspan` and `colspan` | 2 |
| `Q1-A4.html` | HTML form with submission and file upload | 2 |
| `Q1-A5.html` | Bootstrap grid, themes and carousel | 2 |
| `Q1-A6.html` | Bootstrap horizontal form layout | 1 |
| `Q1-A7.html` | `iframe` and the `target` attribute | 1 |

### Q2. JavaScript (13 marks)

| File | Question | Marks |
| :--- | :--- | :---: |
| `Q2-A1.html` | Data types, keywords and operators | 2 |
| `Q2-A2.html` | Conditional statements and loops | 2 |
| `Q2-A3.html` | Functions, parameters, return values and variable scope | 2 |
| `Q2-A4.html` | Arrays and array access methods | 2 |
| `Q2-A5.html` | Objects and properties | 2 |
| `Q2-A6.html` | Regular expressions for input validation | 3 |

## Assignment 2: DOM, jQuery and JSON

### Q1. Document Object Model (10 marks)

| File | Question | Marks |
| :--- | :--- | :---: |
| `Q1-A1.html` | DOM access and manipulation methods | 2 |
| `Q1-A2.html` | Event listeners and event flow | 2 |
| `Q1-A3.html` | Event bubbling and capturing | 2 |
| `Q1-A4.html` | DOM events: onclick, onload, onmouseover, onmouseout, onmouseup, onmousedown | 2 |
| `Q1-A5.html` | Form processing and validation | 1 |
| `Q1-A6.html` | `alert()`, `confirm()` and `prompt()` | 1 |

### Q2. jQuery (8 marks)

| File | Question | Marks |
| :--- | :--- | :---: |
| `Q2-A1.html` | jQuery introduction, installation and syntax | 1 |
| `Q2-A2.html` | Selectors: `*`, element, `#id`, `.class` | 2 |
| `Q2-A3.html` | Event methods: `click`, `dblclick`, `blur`, `change`, `die`, `error` | 2 |
| `Q2-A4.html` | DOM manipulation with jQuery | 2 |
| `Q2-A5.html` | Advantages and disadvantages of jQuery | 1 |

### Q3. JSON (7 marks)

| File | Question | Marks |
| :--- | :--- | :---: |
| `Q3-A1.html` | JSON and its characteristics | 1 |
| `Q3-A2.html` | JSON dataset with 15 records | 2 |
| `Q3-A3.html` | JSON objects, arrays, values and syntax rules | 1 |
| `Q3-A4.html` | `JSON.parse()` and `JSON.stringify()` | 2 |
| `Q3-A5.html` | Advantages and disadvantages of JSON | 1 |

---

## Features of the showcase website

- YouTube-style home page with live preview thumbnails for every program
- Sidebar navigation by assignment and question
- Player page with a browser-style frame and **desktop / tablet / phone** size switch
- **Source code** tab with line numbers and a copy button
- Search with suggestions (press `/` to focus the search box)
- Favorites and recently opened list, saved in the browser
- Light and dark mode
- Previous / next navigation, with keyboard arrow keys
- Fully responsive layout
- Built with plain HTML, CSS and JavaScript in one file, with no frameworks or build step

## Technologies

HTML5, CSS3, JavaScript (ES6), Bootstrap 5.3.3, jQuery 4.0.0 and JSON.

Each assignment page has its own colour theme, so every program looks different.

## Project structure

```text
web-techniques-lab/
├── index.html                  # The showcase website (HTML, CSS and JS in one file)
├── README.md
├── Assignment-1-Answers.txt    # Written answers for Assignment 1
├── Assignment-2-Answers.txt    # Written answers for Assignment 2
├── Assignment-1-HTML-files/    # Q1-A1 to Q1-A7 and Q2-A1 to Q2-A6
└── Assignment-2-HTML-files/    # Q1-A1 to Q1-A6, Q2-A1 to Q2-A5 and Q3-A1 to Q3-A5
    └── js/
        └── jquery-4.0.0.min.js # Local copy of jQuery
```

## Run it locally

The source-code viewer reads files with `fetch()`, so open the project through a local web server and not by double-clicking `index.html`.

**Option 1: VS Code Live Server**
1. Install the *Live Server* extension.
2. Right-click `index.html` and choose **Open with Live Server**.

**Option 2: Python**
```bash
python -m http.server 5500
```
Then open http://localhost:5500

Each program is also a standalone page, so any file inside the two assignment folders can be opened directly in a browser.

## Deploy

This is a static site, so it needs no build step.

**Vercel**
1. Import this GitHub repository.
2. Framework preset: **Other**.
3. Leave the build command and output directory empty.
4. Click **Deploy**.

## Good to know

- Some pages load Bootstrap or images from a CDN, so an internet connection is needed for them.
- The form in `Assignment-1-HTML-files/Q1-A4.html` has no server script behind it, so submitting it shows a 404 page. The form markup is what is being demonstrated.
- The jQuery pages load `js/jquery-4.0.0.min.js` and fall back to the official CDN if that file is missing.
- Some websites refuse to open inside an `iframe`. A blank frame in `Assignment-1-HTML-files/Q1-A7.html` means that site blocks embedding.

## Author

**Your Name**
F.Y. M.Sc. (IT), MAEER's MIT Arts, Commerce and Science College, Alandi (D), Pune
GitHub: [@DevSanghavi](https://github.com/DevSanghavi)

## Note

This repository was created for academic learning and demonstration as part of the Web Techniques coursework.