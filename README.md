# 🚀 HTML Revision Sheet

## 📘 1. HTML Basics

- HTML stands for **HyperText Markup Language**
- It is used to structure content on the web
- File extension: `.html`

**Basic Template:**

    <!DOCTYPE html>
     <html>
        <head>
            <title>Page Title</title>
        </head>
        <body>
            <!-- Content goes here -->
        </body>
     </html>***


## 🔖 2. Common HTML Tags

| Tag                          | Description              |
|-----------------------------|--------------------------|
| `<h1>` - `<h6>`             | Headings (h1 is largest) |
| `<p>`                       | Paragraph                |
| `<a>`                       | Anchor (Hyperlink)       |
| `<img>`                     | Image                    |
| `<br>`                      | Line break               |
| `<hr>`                      | Horizontal line          |
| `<b>`, `<strong>`           | Bold text                |
| `<i>`, `<em>`               | Italic text              |
| `<ul>`, `<ol>`, `<li>`      | Lists                    |
| `<div>`                     | Block-level container    |
| `<span>`                    | Inline container         |
| `<input>`, `<form>`, `<button>` | Form Elements        |
| `<table>`, `<tr>`, `<td>`, `<th>` | Tables             |



## ⚙️ 3. HTML Attributes

HTML attributes provide **additional information** about elements. They are written in the start tag of an HTML element.

---

### 🔑 Common HTML Attributes

| Attribute      | Description                                         |
|----------------|-----------------------------------------------------|
| `href`         | Specifies the URL of a link (`<a>` tag)             |
| `src`          | Specifies the path to an image/media (`<img>`, `<video>`) |
| `alt`          | Alternative text for images                         |
| `id`           | Unique identifier for an element                    |
| `class`        | Used to group elements with the same style          |
| `style`        | Inline CSS styling                                  |
| `title`        | Tooltip text shown on hover                         |
| `type`         | Type of input field/button (e.g., `text`, `submit`) |
| `value`        | Default value of an input field                     |
| `placeholder`  | Hint text shown inside input                        |
| `name`         | Name of the form element (used in form submission)  |
| `disabled`     | Disables an element                                 |
| `readonly`     | Makes input non-editable                           |
| `required`     | Makes input field mandatory                         |

---

### 💡 Example:

    <img src="logo.png" alt="Logo" width="100" height="100" />
       <a href="https://example.com" title="Visit Site">Click Here</a>
       <input type="text" placeholder="Enter your name" required />


## 📝 4. Forms

HTML forms allow users to send data to a server or process it within a webpage. It includes various input fields like text boxes, radio buttons, checkboxes, dropdowns, etc.

---

### 📌 Basic Example:


     <form>
         <label for="name">Name:</label>
         <input type="text" id="name" name="name" />
         <button type="submit">Submit</button>
     </form>



## 🧱 5. Semantic HTML5 Tags

Semantic HTML5 tags help in structuring web content in a meaningful way. These tags improve accessibility, search engine optimization (SEO), and overall code readability.

---

### 🔑 Common Semantic HTML5 Tags:

| Tag        | Description                                                      |
|------------|------------------------------------------------------------------|
| `<header>` | Defines the header of a page or section (often contains navigation, logo, etc.) |
| `<footer>` | Defines the footer of a page or section (often contains copyright, links, etc.) |
| `<nav>`    | Defines a section for navigation links                           |
| `<main>`   | Represents the dominant content of the `<body>` (unique and important content) |
| `<section>`| Represents a section of content (usually with a heading)         |
| `<article>`| Represents a complete, self-contained piece of content (e.g., blog post, news article) |
| `<aside>`  | Represents content tangentially related to the content around it (e.g., sidebars, advertisements) |

---

### 📝 Example:


    <header>
       <h1>Welcome to My Website</h1>
     <nav>
      <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
     </nav>
     </header>

    <main>
       <section>
          <h2>About Us</h2>
         <p>I am Anil Kumar full stack developer.</p>
     </section>

      <article>
        <h2>Our Latest Blog Post</h2>
        <p>Check out our latest post about HTML5 tags!</p>
       </article>
      </main>

     <aside>
       <h3>Advertisement</h3>
        <p>Buy the best web development courses!</p>
     </aside>

     <footer>
           <p>&copy; 2025 My Website</p>
      </footer>


## 🎧 6. Multimedia Elements

    <img src="image.jpg" alt="Image" />
     <audio controls src="audio.mp3"></audio>
     <video controls width="400" src="video.mp4"></video>




## 🌐 7. Meta Tags

Meta tags are used for SEO, responsive web design, and providing additional information to browsers and search engines.



### 🔑 Common Meta Tags:

| Tag                                              | Description                                      |
|--------------------------------------------------|--------------------------------------------------|
| `<meta charset="UTF-8" />`                       | Specifies the character encoding for the document |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0" />` | Controls layout on mobile browsers for responsiveness |
| `<meta name="description" content="This is a website." />` | Provides a short description of the webpage (used for SEO) |

---

### 📝 Example:


        <meta charset="UTF-8" />
         <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <meta name="description" content="This is a website." />
