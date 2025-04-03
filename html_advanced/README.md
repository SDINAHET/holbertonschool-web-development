# 📄 HTML Advanced - Holberton School Project

![HTML Project Badge](https://img.shields.io/badge/Project%20Status-In%20Progress-blue)
![Made With HTML](https://img.shields.io/badge/Made%20with-HTML5-orange)
![Author](https://img.shields.io/badge/Author-Stéphane%20Dinahet-lightgrey)
![Manual Review](https://img.shields.io/badge/Manual%20QA%20Review-Required-red)

---

## 🎯 Project Overview

This project is part of the **Front-End Curriculum at Holberton School**. The objective is to build the **semantic HTML structure of a website** based on a Figma wireframe.

**No CSS or JavaScript** will be used at this stage — only semantic and valid HTML code following accessibility and best practices.

---

## 📚 Learning Objectives

At the end of this project, you should be able to explain:

- ✅ What is HTML?
- ✅ How to create an HTML page from a wireframe
- ✅ What is a markup language?
- ✅ What is the DOM?
- ✅ What is an element/tag?
- ✅ What is an attribute?
- ✅ The purpose of each HTML tag

---

## 📁 Project Files

- `index.html` – Main HTML structure of the page
- `README.md` – Project overview and objectives

---

## 🧩 Project Tasks

| # | Task Name         | Description                                                                 | Status |
|---|-------------------|-----------------------------------------------------------------------------|--------|
| 0 | README & Objectives | Write a professional README for the project                                | ✅     |
| 1 | Header            | Build the website’s header (logo + nav links)                               | ✅     |
| 2 | Banner            | Build the banner section with hero text and statistics                      | ✅     |
| 3 | Quote             | Create the quote section with image, quote and author name                  | ✅     |
| 4 | Videos            | Display the list of video previews with authors and ratings                 | ✅     |
| 5 | Membership        | Section promoting membership options with call-to-actions                   | ✅     |
| 6 | FAQ               | Frequently Asked Questions section with two rows of Q&A                     | ✅     |
| 7 | Footer            | Footer with logo, social media icons, and copyright                         | ✅     |

---

## 🧠 Technologies Used

- HTML5 (Semantic tags only)
- [W3C Validator](https://validator.w3.org/) for code validation
- Figma for wireframe reference

> ⚠️ **No external libraries allowed** (e.g., Bootstrap, React, etc.)

---

## 🖼️ Figma Design

- [🌐 View Final Wireframe (Figma)](https://www.figma.com/file/3E02P6NmkAG0DzYlC1FuxG/HTML-Advanced?type=design&node-id=1-2)
- Make sure to **Duplicate to Drafts** in Figma to edit and inspect design details.

---

## 📝 Requirements

- ✅ Each file must end with a new line
- ✅ Use semantic HTML structure (header, main, section, article, footer, etc.)
- ✅ All HTML must pass the **W3C validator**
- ❌ No CSS, JavaScript, frameworks, or libraries allowed

---

## 🧪 Validation & QA

- HTML code must be W3C-compliant
- File: [https://validator.w3.org/](https://validator.w3.org/)
- Submit for manual QA review on the Holberton platform once completed

---

## 👨‍💻 Author

**Stéphane Dinahet**  
📍 Holberton School - Rennes, France  
🔗 [GitHub](https://github.com/SDINAHET) | [LinkedIn](https://www.linkedin.com/in/st%C3%A9phane-dinahet-3b363189/)

---

## 🔗 Useful Resources

- [MDN Web Docs - HTML Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)
- [HTML Semantic Elements](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html)
- [Learn to Code HTML & CSS](https://learn.shayhowe.com/html-css/building-your-first-web-page/)

---

> 🧠 **Pro Tip:** Even though there is no CSS yet, structure your HTML carefully and use semantic elements to prepare for upcoming styling phases.



---

## 🧩 Task Breakdown (with Full Instructions)

---

### 🔹 0. `README.md` and Objectives

> **Description**:  
Write a professional README that includes:
- Project summary and objectives
- Tech/tools used
- List of tasks
- Resources and validation tools

📁 Expected file: `html_advanced/README.md`

---

### 🔹 1. Header

> **Instructions**:  
Start building the **header** of the website.

- Create the base structure: `<html>`, `<head>`, `<body>`
- Inside `<body>`, add:
  - A `<header>` tag
  - A `<a>` link containing a logo `<img>`
  - A block with **3 navigation links**

📁 Expected file: `html_advanced/index.html`

---

### 🔹 2. Banner

> **Instructions**:  
Create the **hero section** inside the `<main>` tag:

- One block containing:
  - A `<h1>` title
  - A text element
  - A `<button>`
- Another block containing:
  - A `<h2>` subtitle
  - A container with **4 sub-blocks**, each including:
    - An **image**
    - A `<h3>` title
    - A description

📁 Expected file: `html_advanced/index.html`

---

### 🔹 3. Quote Section

> **Instructions**:  
Add a **quote block** below the banner:

- Inside `<main>`, create a new `<section>`
- Add:
  - An image
  - A block containing:
    - A `<blockquote>` tag
    - A text element for the quote author
    - Additional descriptive text

📁 Expected file: `html_advanced/index.html`

---

### 🔹 4. Videos List

> **Instructions**:  
Create a section with **4 video preview blocks**:

- A `<section>` containing:
  - A `<h1>` heading
  - A container with 4 video blocks, each including:
    - An image
    - A `<h2>` title
    - A short text
    - An author block:
      - Image (author)
      - `<h3>` name
      - A rating block with:
        - Star images (1 per star)
        - Text description

📁 Expected file: `html_advanced/index.html`

---

### 🔹 5. Membership Offers

> **Instructions**:  
Create a section promoting **membership plans**:

- A `<section>` with:
  - A `<h1>` heading
  - A container with **4 blocks**, each containing:
    - An image
    - A `<h2>` title
    - A description
    - A `<button>` call-to-action

📁 Expected file: `html_advanced/index.html`

---

### 🔹 6. FAQ Section

> **Instructions**:  
Add a **Frequently Asked Questions** section:

- A `<section>` with:
  - A `<h1>` heading
  - A container with **2 row blocks**
    - Each row contains 2 "question items":
      - A `<h2>` heading (question)
      - A paragraph (answer)

💡 Note: There’s no such thing as `<row>` in HTML — "row" refers to the layout only.

📁 Expected file: `html_advanced/index.html`

---

### 🔹 7. Footer

> **Instructions**:  
Add the **footer** of the website:

- Outside of `<main>`, add a `<footer>` with:
  - A centering block
  - Inside it:
    - A logo image
    - A block with:
      - 3 social media icons (images inside `<a>` links)
      - A copyright

📁 Expected file: `html_advanced/index.html`

---

## 🧪 Recommended Tools

- ✅ [W3C Validator](https://validator.w3.org/)
- ✅ [Figma Inspector](https://www.figma.com/)


