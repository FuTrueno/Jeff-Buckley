# Jeff Buckley — Grace & Legacy

## Assignment #2: Three-Page Website Using HTML and CSS

This project is a three-page Jeff Buckley themed website created for the Web Technologies assignment. It uses semantic HTML, multimedia, a table, a form, and all three required CSS methods.

### What is CSS?
CSS (Cascading Style Sheets) is a stylesheet language used to control the presentation of HTML documents. It separates presentation from document structure, making pages easier to style consistently and maintain. CSS can control colors, typography, spacing, borders, dimensions, layouts, and interactive states.

One rule used in this project is `input[type="email"] { border-left: 3px solid #b8a98d; }`. The selector is `input[type="email"]`, the property is `border-left`, and the value is `3px solid #b8a98d`.

### Three CSS methods
Page 1 (`index.html`) uses **inline CSS**, where styles are written directly in HTML elements through the `style` attribute. Page 2 (`information.html`) uses **embedded CSS**, where rules are placed inside a `<style>` element in the document head. Page 3 (`registration.html`) uses **external CSS**, linking to `style.css`. External CSS is generally easier to maintain across multiple pages, while inline CSS has the narrowest scope.

### CSS history
CSS1 introduced the core stylesheet model and basic selectors and properties. CSS2 and CSS2.1 expanded layout, media handling, positioning, and other presentation capabilities. Modern CSS is developed as modular specifications, allowing newer features such as flexible layouts, responsive design, and more advanced selectors to evolve independently.

### Browser support
Browser support matters because the same HTML and CSS should produce a usable result across different rendering engines. The website should be tested in **Google Chrome** and **Microsoft Edge** before submission, with any differences recorded after actual testing.

### Semantic HTML
Examples of semantic HTML in this project include `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, and `<footer>`. A non-semantic example is `<div>`, which is used as a generic grouping container where no more meaningful semantic element is appropriate.

### Submission/testing checklist
- Validate all three HTML files with the W3C Markup Validation Service.
- Test required form fields, invalid email input, and passwords shorter than eight characters.
- Test navigation and media playback.
- Test the site in Chrome and Edge and record differences.
- Publish the completed folder through GitHub Pages.
