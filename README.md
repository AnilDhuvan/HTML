# HTML Revision Sheet

## 1. HTML Basics

HTML stands for HyperText Markup Language.
HTML is not a programming language, it's a markup language.
File extension: .html

Basic structure:

<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <!-- Content goes here -->
  </body>
</html>

## 2. Most Used Tags

Headings: <h1> to <h6>
Paragraph: <p>
Anchor: <a>
Image: <img>
Line Break: <br>
Horizontal Line: <hr>
Bold: <strong> or <b>
Italic: <em> or <i>
Lists: <ul>, <ol>, <li>
Div and Span: <div>, <span>
Input fields: <input>, <form>, <button>
Table: <table>, <tr>, <td>, <th>

## 3. Attributes

Attributes provide additional info about elements.
Examples: href, src, alt, id, class, style, type, name, value, placeholder
Example:
<img src='logo.png' alt='Logo' width='100' height='100'>

## 4. Forms (Basic Controls)

Form elements:
<input>, <textarea>, <select>, <option>, <label>
Example:

<form>
  <label for='name'>Name:</label>
  <input type='text' id='name'>
  <button type='submit'>Submit</button>
</form>

## 5. Semantic Tags

HTML5 Semantic Elements make code more readable:

<header>, <footer>, <nav>, <main>, <section>, <article>, <aside>

## 6. Multimedia

<img src='image.jpg' alt='pic'>
<audio controls src='audio.mp3'></audio>
<video controls width='400' src='video.mp4'></video>

## 7. Meta Tags

Placed inside <head> for SEO and responsiveness:

<meta charset='UTF-8'>
<meta name='viewport' content='width=device-width, initial-scale=1.0'>
<meta name='description' content='This is a website.'>

## 8. HTML Entities

Use for special characters:
&lt; = <
&gt; = >
&nbsp; = space
&copy; = ©

## 9. Comment in HTML

<!-- This is a comment -->

## 10. Best Practices

- Use semantic tags
- Add alt for images
- Structure code with divs/sections
- Avoid inline styles
