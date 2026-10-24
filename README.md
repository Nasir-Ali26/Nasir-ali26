
# Hi, I'm Nasir Ali 👋

### Front-End Web Developer | Learner | Nature Lover

Welcome to my GitHub profile!

I'm Nasir Ali, a Front-End Web Developer passionate about
creating modern, responsive, and user-friendly websites.

## 👨‍💻 About Me

- 🌐 I love Front-End Web Development.
- 💻 Currently learning HTML, CSS, and JavaScript.
- 🔐 Interested in Ethical Hacking and Cybersecurity.
- 🏔️ Mountain lover and nature enthusiast.
- 🌿 I enjoy exploring nature and beautiful landscapes.
- 🚀 Building projects to improve my coding skills.

## 🛠️ My Skills

- HTML5
- CSS3
- JavaScript
- Responsive Web Design
- Git and GitHub
- 
# HTML Fundamentals — Complete Beginner's Guide

**Author:** Nasir Ali  
**Field:** Front-End Web Development  
**Level:** Beginner  
**Practice Tools:** VS Code and Web Browser

## About This Repository

This repository contains my HTML Fundamentals learning notes, practical code examples, and a complete mini project. It covers the essential HTML tags and concepts required to build the structure of a website.

My goal is to improve my front-end development skills through consistent learning and hands-on coding practice.

## Table of Contents

1. [Introduction to HTML](#1-introduction-to-html)
2. [Basic HTML Structure](#2-basic-html-document-structure)
3. [Tags, Elements, and Attributes](#3-html-tags-elements-and-attributes)
4. [Heading Tags](#4-heading-tags)
5. [Paragraphs and Line Breaks](#5-paragraphs-and-line-breaks)
6. [Text Formatting](#6-text-formatting-tags)
7. [HTML Comments](#7-html-comments)
8. [Links](#8-html-links)
9. [Images](#9-html-images)
10. [Lists](#10-html-lists)
11. [Tables](#11-html-tables)
12. [Semantic HTML](#12-semantic-html)
13. [HTML Forms](#13-html-forms)
14. [Audio and Video](#14-audio-and-video)
15. [HTML Entities](#15-html-entities)
16. [Best Practices](#16-html-best-practices)
17. [Mini Project: Personal Portfolio](#17-mini-project-personal-portfolio)
18. [Practice Tasks](#18-practice-tasks)
19. [Learning Roadmap](#19-learning-roadmap)

---

## 1. Introduction to HTML

HTML stands for **HyperText Markup Language**.

HTML is used to define the structure and content of web pages. It tells the browser how content should be organized, such as headings, paragraphs, images, links, lists, tables, and forms.

### HTML Example

```html
<h1>My First Website</h1>
<p>I am learning HTML.</p>
<a href="https://www.github.com">Visit GitHub</a>
```

### HTML vs CSS vs JavaScript

| Technology | Purpose |
|---|---|
| HTML | Creates the structure of a webpage |
| CSS | Controls design, colors, spacing, and layout |
| JavaScript | Adds behavior and interactivity |

## 2. Basic HTML Document Structure

Every standard HTML page starts with a basic document structure.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
</head>
<body>

    <h1>Welcome to My Website</h1>
    <p>This is my first webpage.</p>

</body>
</html>
```

### Explanation

- `<!DOCTYPE html>` declares an HTML5 document.
- `<html>` is the root element.
- `<head>` contains metadata and linked resources.
- `<meta charset="UTF-8">` defines character encoding.
- The viewport meta tag helps the page display correctly on mobile devices.
- `<title>` sets the browser tab title.
- `<body>` contains the visible webpage content.

**Important:** `<head>` and `<header>` have different purposes. The head contains metadata, while the header is a visible introductory section.

## 3. HTML Tags, Elements, and Attributes

### Tags and Elements

```html
<p>Hello World</p>
```

- `<p>` is the opening tag.
- `</p>` is the closing tag.
- `Hello World` is the content.
- The complete structure is an HTML element.

### Attributes

Attributes provide additional information about elements.

```html
<a href="https://www.github.com" target="_blank"
   rel="noopener noreferrer">Open GitHub</a>
```

- `href` defines the link destination.
- `target="_blank"` generally opens the link in a new tab.
- `rel="noopener noreferrer"` provides additional protection and privacy for the new browsing context.

### Void Elements

Some HTML elements do not require closing tags.

```html
<img src="photo.jpg" alt="Profile photo">
<br>
<hr>
<input type="text">
```

Examples include `<img>`, `<br>`, `<hr>`, and `<input>`.

## 4. Heading Tags

HTML provides six heading levels, from `<h1>` to `<h6>`.

```html
<h1>Main Heading</h1>
<h2>Section Heading</h2>
<h3>Subsection Heading</h3>
<h4>Heading Level 4</h4>
<h5>Heading Level 5</h5>
<h6>Heading Level 6</h6>
```

Use headings to organize content logically. The main page heading is generally an `<h1>`, while `<h2>` and lower levels organize subsections.

## 5. Paragraphs and Line Breaks

```html
<p>My name is Nasir Ali.</p>

<p>I am learning front-end web development.</p>

<p>First line<br>Second line</p>

<hr>

<p>This is a new topic.</p>
```

| Tag | Purpose |
|---|---|
| `<p>` | Creates a paragraph |
| `<br>` | Creates a line break |
| `<hr>` | Represents a thematic break |

Use separate paragraphs for separate ideas rather than using repeated line breaks for spacing.

## 6. Text Formatting Tags

```html
<p><strong>Important text</strong></p>
<p><em>Emphasized text</em></p>
<p><b>Bold text</b></p>
<p><i>Italic text</i></p>
<p><u>Underlined text</u></p>
<p><mark>Highlighted text</mark></p>
<p><del>Old price: Rs. 2000</del></p>
<p><ins>New price: Rs. 1500</ins></p>
<p>Water formula: H<sub>2</sub>O</p>
<p>Mathematics: x<sup>2</sup></p>
<p><small>Small print text</small></p>
```

These tags provide different meanings and presentations:

- `<strong>` indicates importance.
- `<em>` indicates emphasis.
- `<b>` and `<i>` draw attention or distinguish text without necessarily expressing importance or emphasis.
- `<u>` underlines text.
- `<mark>` highlights text.
- `<del>` and `<ins>` represent deleted and inserted content.
- `<sub>` and `<sup>` represent subscript and superscript.
- `<small>` represents side comments or small print.

## 7. HTML Comments

Comments help developers document their code.

```html
<!-- This is an HTML comment -->

<h1>My Portfolio</h1>

<!-- About section -->
<section>
    <h2>About Me</h2>
</section>
```

Comments are not displayed as normal visible page content in the browser.

## 8. HTML Links

The `<a>` element creates hyperlinks.

```html
<!-- External link -->
<a href="https://www.github.com">GitHub</a>

<!-- Open in a new tab -->
<a href="https://www.google.com"
   target="_blank"
   rel="noopener noreferrer">Google</a>

<!-- Email link -->
<a href="mailto:example@email.com">Send Email</a>

<!-- Phone link -->
<a href="tel:+923001234567">Call Me</a>

<!-- Link to a section -->
<a href="#contact">Go to Contact</a>

<section id="contact">
    <h2>Contact Me</h2>
</section>
```

The `href` attribute defines the destination. An element's `id` can identify a section for navigation.

## 9. HTML Images

The `<img>` element embeds an image.

```html
<img src="images/nature.jpg"
     alt="Green mountains and forest"
     width="400">
```

### Important Image Attributes

- `src`: Path to the image.
- `alt`: Text alternative describing the image.
- `width`: Image width.
- `height`: Image height.
- `loading="lazy"`: Allows an image to load lazily when appropriate.

Example project structure:

```text
my-website/
├── index.html
└── images/
    └── nature.jpg
```

Use this path in HTML:

```html
<img src="images/nature.jpg" alt="Mountain landscape">
```

Meaningful alternative text improves accessibility and helps when an image cannot load.

## 10. HTML Lists

### Unordered List

```html
<h2>My Hobbies</h2>

<ul>
    <li>Coding</li>
    <li>Hiking</li>
    <li>Nature Photography</li>
</ul>
```

`<ul>` creates a bulleted list, while `<li>` defines each list item.

### Ordered List

```html
<h2>Steps to Create a Website</h2>

<ol>
    <li>Plan the website</li>
    <li>Write HTML</li>
    <li>Style with CSS</li>
    <li>Test in a browser</li>
</ol>
```

`<ol>` creates a numbered list.

### Description List

```html
<dl>
    <dt>HTML</dt>
    <dd>Defines webpage structure.</dd>

    <dt>CSS</dt>
    <dd>Controls webpage presentation.</dd>
</dl>
```

- `<dl>` creates a description list.
- `<dt>` defines a term.
- `<dd>` provides its description.

## 11. HTML Tables

Tables organize data into rows and columns.

```html
<table>
    <caption>My Learning Progress</caption>

    <thead>
        <tr>
            <th>Topic</th>
            <th>Status</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>HTML Basics</td>
            <td>Completed</td>
        </tr>
        <tr>
            <td>HTML Forms</td>
            <td>Practicing</td>
        </tr>
    </tbody>
</table>
```

| Tag | Purpose |
|---|---|
| `<table>` | Creates the table |
| `<caption>` | Provides a table title |
| `<thead>` | Groups header rows |
| `<tbody>` | Groups main data rows |
| `<tr>` | Creates a row |
| `<th>` | Defines a header cell |
| `<td>` | Defines a data cell |
| `<tfoot>` | Groups footer rows when needed |

Tables should be used for tabular data, not for general page layout.

## 12. Semantic HTML

Semantic HTML elements describe the purpose of different parts of a webpage.

```html
<header>
    <h1>My Portfolio</h1>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
</nav>

<main>
    <section id="about">
        <h2>About Me</h2>
        <p>I am learning front-end development.</p>
    </section>

    <article>
        <h2>My Latest Project</h2>
        <p>A website built with HTML and CSS.</p>
    </article>

    <aside>
        <p>Related learning resources.</p>
    </aside>
</main>

<footer>
    <p>&copy; 2026 Nasir Ali</p>
</footer>
```

### Common Semantic Elements

- `<header>`: Introductory content.
- `<nav>`: Navigation links.
- `<main>`: Primary content of the page.
- `<section>`: A thematic group of content.
- `<article>`: Self-contained content.
- `<aside>`: Related supplementary content.
- `<footer>`: Footer information.
- `<figure>`: Self-contained media or illustration.
- `<figcaption>`: Caption for a figure.
- `<time>`: Represents a date or time.

### Other Useful Elements

```html
<div>A general block container</div>

<p>This is <span>an inline element</span> example.</p>

<details>
    <summary>What is HTML?</summary>
    <p>HTML defines webpage structure.</p>
</details>
```

`<div>` is a general-purpose block container, while `<span>` is a general-purpose inline container. Use semantic elements whenever their meaning fits the content.

## 13. HTML Forms

Forms collect information from users.

```html
<form action="#" method="get">
    <label for="fullname">Full Name:</label>
    <input type="text"
           id="fullname"
           name="fullname"
           required>

    <br><br>

    <label for="email">Email:</label>
    <input type="email"
           id="email"
           name="email"
           required>

    <br><br>

    <label for="password">Password:</label>
    <input type="password"
           id="password"
           name="password"
           required>

    <br><br>

    <button type="submit">Register</button>
</form>
```

### Important Form Attributes

- `action`: Destination for submitted form data.
- `method`: HTTP method, commonly `get` or `post`.
- `name`: Name used to identify submitted fields.
- `required`: Makes a field required during browser validation.
- `placeholder`: Provides a short hint.
- `id`: Identifies an element.
- `for`: Connects a label to its corresponding form control.

**Note:** `action="#"` is a learning example, not a working registration backend.

### Common Input Types

```html
<input type="text" placeholder="Your name">
<input type="email" placeholder="Your email">
<input type="password" placeholder="Your password">
<input type="number" min="1" max="100">
<input type="date">
<input type="file">
<input type="color">
<input type="checkbox"> I agree

<input type="radio" name="level" value="beginner">
Beginner

<input type="radio" name="level" value="advanced">
Advanced

<input type="submit" value="Submit">
<input type="reset" value="Reset">
```

### Dropdown, Textarea, and Buttons

```html
<label for="course">Choose a course:</label>

<select id="course" name="course">
    <option value="html">HTML</option>
    <option value="css">CSS</option>
    <option value="javascript">JavaScript</option>
</select>

<br><br>

<label for="message">Your Message:</label>

<textarea id="message"
          name="message"
          rows="4"
          cols="30"></textarea>

<br><br>

<button type="button">Normal Button</button>
<button type="submit">Submit Form</button>
<button type="reset">Reset Form</button>
```

- `<select>` creates a dropdown.
- `<option>` defines an option.
- `<textarea>` accepts multiline text.
- A button with `type="button"` does not automatically submit a form.
- `type="submit"` submits the form.
- `type="reset"` resets form controls to their initial values.

## 14. Audio and Video

HTML supports embedded audio and video.

### Audio

```html
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support audio.
</audio>
```

### Video

```html
<video controls width="400">
    <source src="video.mp4" type="video/mp4">
    Your browser does not support video.
</video>
```

The `controls` attribute displays playback controls. Video elements can also include captions using the `<track>` element.

### Iframe

An iframe embeds another webpage or supported content.

```html
<iframe
    src="https://www.youtube.com/embed/VIDEO_ID"
    title="HTML Tutorial"
    width="560"
    height="315"
    allowfullscreen>
</iframe>
```

Replace `VIDEO_ID` with the actual YouTube video ID. The source website must allow embedding.

## 15. HTML Entities

HTML entities represent reserved characters and special symbols.

| Entity | Output |
|---|---|
| `&copy;` | © |
| `&amp;` | & |
| `&lt;` | < |
| `&gt;` | > |
| `&nbsp;` | Non-breaking space |
| `&quot;` | " |

Example:

```html
<p>&copy; 2026 Nasir Ali</p>
<p>HTML &amp; CSS</p>
<p>Use &lt;h1&gt; for a main heading.</p>
```

## 16. HTML Best Practices

1. Always declare `<!DOCTYPE html>`.
2. Use a meaningful page title.
3. Set the correct document language.
4. Use semantic HTML where appropriate.
5. Provide useful alternative text for meaningful images.
6. Associate labels with form controls.
7. Use headings in a logical order.
8. Keep CSS in a separate stylesheet when appropriate.
9. Test the webpage on desktop and mobile screens.
10. Use a browser's developer tools to identify problems.
11. Validate HTML using the [W3C Markup Validation Service](https://validator.w3.org/).
12. Never treat front-end form validation as a replacement for server-side validation and security.

---

# 17. Mini Project: Personal Portfolio

**Project Name:** Nasir Ali — Front-End Developer Portfolio

### Project Objectives

- Build a complete HTML webpage.
- Practice semantic HTML.
- Create navigation links.
- Display profile information and skills.
- Organize projects using article elements.
- Create a contact form.
- Connect an external CSS file.

### Project Structure

```text
nasir-portfolio/
├── index.html
├── style.css
└── images/
    └── profile.jpg
```

### `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Nasir Ali's front-end development portfolio">
    <title>Nasir Ali | Front-End Developer</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="header">
        <a href="#home" class="logo">Nasir.</a>

        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <main>
        <section id="home" class="hero">
            <div>
                <p>FRONT-END WEB DEVELOPER</p>
                <h1>Hello, I'm Nasir Ali.</h1>
                <p>
                    I create modern, responsive and
                    user-friendly websites.
                </p>
                <a href="#projects" class="btn">View Projects</a>
            </div>

            <figure>
                <img src="images/profile.jpg"
                     alt="Nasir Ali profile photo"
                     width="250">
                <figcaption>Learning and building every day.</figcaption>
            </figure>
        </section>

        <section id="about" class="section">
            <h2>About Me</h2>
            <p>
                I am Nasir Ali, CEO and Founder of Zindan Company.
                I specialize in front-end web development and
                creating modern, responsive and user-friendly
                websites for businesses and individuals.
            </p>
            <p>I enjoy hiking, mountains and nature.</p>
        </section>

        <section id="skills" class="section">
            <h2>My Skills</h2>
            <ul>
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>Responsive Design</li>
                <li>Git and GitHub</li>
            </ul>
        </section>

        <section id="projects" class="section">
            <h2>My Projects</h2>

            <article class="project-card">
                <h3>Restaurant Website</h3>
                <p>A website for restaurant information and menus.</p>
                <p>Technologies: HTML and CSS</p>
            </article>

            <article class="project-card">
                <h3>Online Shoe Store</h3>
                <p>A product display page for an online shoe store.</p>
                <p>Technologies: HTML, CSS and JavaScript</p>
            </article>

            <article class="project-card">
                <h3>Personal Portfolio</h3>
                <p>A website to showcase my skills and work.</p>
                <p>Technologies: HTML and CSS</p>
            </article>
        </section>

        <section id="contact" class="section">
            <h2>Contact Me</h2>

            <form action="#" method="get">
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Your Email</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Your Message</label>
                <textarea id="message" name="message"
                          rows="5" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2026 Nasir Ali. All rights reserved.</p>
        <a href="https://github.com/">GitHub</a>
    </footer>

</body>
</html>
```

### `style.css`

```css
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background: #f5f4ec;
    color: #26382d;
    line-height: 1.7;
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    gap: 18px;
    padding: 20px 8%;
    background: #1e382a;
    color: white;
}

.logo {
    color: white;
    font-size: 26px;
    font-weight: bold;
    text-decoration: none;
}

nav {
    display: flex;
    flex-wrap: wrap;
    gap: 18px;
}

nav a {
    color: white;
    text-decoration: none;
}

nav a:hover {
    color: #a6d58b;
}

.hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 35px;
    padding: 65px 8%;
    background: linear-gradient(120deg, #e1ebd9, #f5f4ec);
}

.hero h1 {
    font-size: clamp(32px, 5vw, 52px);
    margin: 15px 0;
}

.hero img {
    width: 250px;
    max-width: 100%;
    height: auto;
    border-radius: 50%;
}

.btn,
button {
    display: inline-block;
    margin-top: 18px;
    padding: 12px 20px;
    border: none;
    border-radius: 7px;
    background: #315b3d;
    color: white;
    text-decoration: none;
    cursor: pointer;
}

.section {
    padding: 55px 8%;
    scroll-margin-top: 20px;
}

.section h2 {
    margin-bottom: 18px;
}

.section ul {
    padding-left: 22px;
}

.project-card {
    margin: 18px 0;
    padding: 22px;
    background: white;
    border-radius: 10px;
    box-shadow: 0 5px 20px #26382d15;
    transition: transform 0.3s;
}

.project-card:hover {
    transform: translateY(-4px);
}

form {
    display: grid;
    gap: 10px;
    max-width: 550px;
}

input,
textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #b9c7b7;
    border-radius: 6px;
    font: inherit;
}

textarea {
    resize: vertical;
}

button {
    justify-self: start;
}

.footer {
    padding: 25px;
    text-align: center;
    background: #1e382a;
    color: white;
}

.footer a {
    color: #c6e5b4;
}

@media (max-width: 650px) {
    .header,
    .hero {
        flex-direction: column;
        text-align: center;
    }

    nav {
        justify-content: center;
    }

    .hero img {
        width: 190px;
    }
}
```

### How to Run the Project

1. Create the `nasir-portfolio` folder in VS Code.
2. Create `index.html` and `style.css`.
3. Paste the corresponding code into each file.
4. Add your profile image to `images/profile.jpg`.
5. Save both files.
6. Open `index.html` in a browser or use VS Code Live Server.
7. Test navigation links, project sections, and the responsive layout.

**Note:** The contact form is a front-end demonstration only. It does not save messages or send emails without a backend or form-processing service.

---

## 18. Practice Tasks

Use these tasks to strengthen your understanding.

- [ ] Create a webpage with all six heading levels.
- [ ] Write five paragraphs about yourself.
- [ ] Add external links to GitHub and other websites.
- [ ] Display three images with suitable alternative text.
- [ ] Create an ordered list of your daily learning tasks.
- [ ] Create an unordered list of your hobbies.
- [ ] Build a table showing your weekly learning progress.
- [ ] Create a registration form with name, email, password, and gender or skill-level options.
- [ ] Add a new section called My Hobbies.
- [ ] Add links to three real portfolio projects.
- [ ] Test the webpage on a mobile screen.
- [ ] Publish the project using GitHub Pages.

## 19. Learning Roadmap

| Stage | Topic | Goal |
|---|---|---|
| Week 1 | HTML Fundamentals | Understand tags and document structure |
| Week 2 | CSS Fundamentals | Learn selectors, colors, spacing, and typography |
| Week 3 | Flexbox and Grid | Build responsive layouts |
| Week 4 | JavaScript Basics | Add interaction and dynamic behavior |
| Week 5 | DOM and Events | Make webpages interactive |
| Week 6 | Git and GitHub | Track code and publish projects |
| Week 7 | Responsive Projects | Build complete responsive websites |

## Conclusion

HTML is the foundation of front-end web development. Learning tags alone is not enough; regular practice and real projects help develop practical skills.

This repository represents my HTML learning journey and provides a foundation for studying CSS, JavaScript, responsive design, and more advanced front-end development.

**Keep learning, keep coding, and keep building.**

— Nasir Ali

⭐ Thanks for visiting my profile!
