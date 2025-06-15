# HTML: Beginner to Expert (Ultimate Guide)

Welcome! This guide covers every essential and advanced HTML concept, explained in simple English. You’ll learn what tags are, how to use them, every type, attributes, forms, tables, and even expert tips. Suitable even for absolute beginners!

---

## 1. What is HTML?

- **HTML** stands for **HyperText Markup Language**.
- It is the standard language to create and structure web pages.
- HTML uses **tags** to mark-up content.

---

## 2. What is a Tag? (Tag Syntax)

- A **tag** tells the browser how to display content.
- **Syntax:**  
  `<tagname>Content</tagname>`
- **Opening tag:** `<tagname>`  
- **Closing tag:** `</tagname>`  
  (Notice the `/` in the closing tag)

### Example

```html
<p>This is a paragraph.</p>
```

---

## 3. Self-Closing Tags (Void Elements)

Self-closing tags do not have closing tags.

- **Syntax:** `<tagname />`

**Examples:**
```html
<img src="logo.png" alt="Logo" />
<br />
<hr />
<input type="text" />
<link rel="stylesheet" href="style.css" />
<meta charset="UTF-8" />
```
**Tip:** In HTML5, you can write `<br>` instead of `<br />`.

---

## 4. Basic HTML Structure

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Web Page</title>
  </head>
  <body>
    <!-- Page content goes here -->
  </body>
</html>
```

- `<!DOCTYPE html>`: Declares the document is HTML5.
- `<html>`: Root element.
- `<head>`: Metadata, links, title.
- `<body>`: Visible page content.

---

## 5. Headings

- From `<h1>` (largest) to `<h6>` (smallest)
```html
<h1>Main Title</h1>
<h2>Section Title</h2>
<h6>Smallest Heading</h6>
```

---

## 6. Paragraphs and Text

```html
<p>This is a paragraph.</p>
```

- **Bold:** `<b>Bold</b>` or `<strong>Strong</strong>`
- **Italic:** `<i>Italic</i>` or `<em>Emphasized</em>`
- **Underline:** `<u>Underline</u>`

---

## 7. Comments

```html
<!-- This is a comment -->
```
- Not displayed on the page.

---

## 8. Lists

### a. Unordered List

```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
</ul>
```

### b. Ordered List

```html
<ol>
  <li>First</li>
  <li>Second</li>
</ol>
```

### c. Description List

```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
</dl>
```

---

## 9. Links

```html
<a href="https://www.example.com">Visit Example</a>
```
- **Attributes:**  
  - `href`: URL to go to  
  - `target="_blank"`: Open in new tab

---

## 10. Images

```html
<img src="cat.jpg" alt="A cute cat" width="200" height="100" />
```
- **Attributes:** `src`, `alt`, `width`, `height`

---

## 11. Block vs Inline Elements

- **Block:** Starts on a new line, takes full width (e.g., `<div>`, `<h1>`, `<p>`, `<ul>`, `<table>`)
- **Inline:** Stays in line, only as wide as needed (e.g., `<span>`, `<a>`, `<img>`, `<b>`, `<i>`)

---

## 12. Grouping & Layout Tags

- **`<div>`**: Block container for grouping.
- **`<span>`**: Inline container for styling small pieces.

---

## 13. Tables

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>24</td>
  </tr>
</table>
```
- `<table>`: Table  
- `<tr>`: Table row  
- `<th>`: Table header  
- `<td>`: Table data

---

## 14. Forms & Inputs

### a. Basic Form

```html
<form action="/submit" method="post">
  <input type="text" name="username" placeholder="Enter name" />
  <input type="submit" value="Submit" />
</form>
```

### b. Input Types

```html
<input type="text" placeholder="Text" />
<input type="number" min="1" max="10" />
<input type="radio" name="gender" value="male" /> Male
<input type="checkbox" /> Accept
<input type="color" />
<input type="datetime-local" />
<input type="file" />
```

### c. Textarea

```html
<textarea rows="4" cols="20" placeholder="Type here"></textarea>
```

### d. Select Dropdown

```html
<select>
  <option value="apple">Apple</option>
  <option value="banana">Banana</option>
</select>
```

---

## 15. Advanced Form Elements

- **`<label for="id">`**: Clickable label for input.
- **`<fieldset>`/`<legend>`**: Group and title form sections.

```html
<fieldset>
  <legend>Personal Info</legend>
  <label for="email">Email:</label>
  <input id="email" type="email" />
</fieldset>
```

---

## 16. Media Elements

### a. Video

```html
<video src="movie.mp4" controls width="400"></video>
```

### b. Audio

```html
<audio src="audio.mp3" controls></audio>
```

---

## 17. Special/Deprecated Tags

- **`<marquee>`**: Scrolls text (deprecated, don’t use in real projects)
- **`<center>`**: Centers content (deprecated)

---

## 18. Semantic HTML

- Use tags that describe meaning:
  - `<header>`, `<footer>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<figure>`, `<figcaption>`

**Example:**
```html
<header>
  <nav>
    <a href="/">Home</a>
  </nav>
</header>
<main>
  <section>
    <h1>Welcome</h1>
  </section>
</main>
<footer>© 2025</footer>
```

---

## 19. Attributes

- Extra information inside a tag.
- **Format:** `<tag attribute="value">`
- Common attributes:  
  - `id`, `class`, `style`, `title`, `placeholder`, `value`, `disabled`, `checked`, `selected`

---

## 20. HTML Entities

- For special characters:
  - `&lt;` = `<`
  - `&gt;` = `>`
  - `&amp;` = `&`
  - `&copy;` = ©

---

## 21. Accessibility Tips

- Always use `alt` for images.
- Use `label` for form fields.
- Use semantic tags for structure.
- Use headings in order (`<h1>`, `<h2>`, ...).

---

## 22. Previewing HTML

- **In Browser:** Double-click the `.html` file or right-click → Open with browser.
- **In VS Code:** Install "Live Server" extension, right-click file → Open with Live Server.

---

## 23. Developer Tools

- **Open Dev Tools:** Press `F12` or right-click → Inspect.
- Use "Elements" tab to edit HTML live and debug layouts.

---

## 24. VS Code Shortcuts

- `!` + Tab: Boilerplate HTML
- `<tag> + Tab`: Autocomplete tag
- `Alt + Shift + Down/Up`: Duplicate line
- `Ctrl + /`: Toggle comment
- `Ctrl + Space`: Suggestions/IntelliSense

---

## 25. Tips & Best Practices

- Close all tags properly.
- Indent code for readability.
- Use semantic HTML for better SEO and accessibility.
- Test your page in multiple browsers.
- Use external CSS/JS, not the `<style>` or `<script>` tags inside `<body>` for large projects.

---

---
