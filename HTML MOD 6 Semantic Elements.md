<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Module 4</title>
    <style>
        body {
            background-color: black;
            color: white;
        }
        h1, h2, h3, h4, h5, h6 {
            color: white;
        }
    </style>
</head>
<body>
## Module 6: HTML Semantic Elements

### `<article>`
The `<article>` tag specifies independent, self-contained content that could be distributed and reused independently.

#### Example
```html
<article>
    <h2>HTML5 Semantic Elements</h2>
    <p>HTML5 introduces several new semantic elements that define the different parts of a web page more clearly.</p>
</article>
```

### `<aside>`
The `<aside>` tag defines some content aside from the content it is placed in. The aside content should be indirectly related to the surrounding content.

#### Example
```html
<aside>
    <h2>Related Articles</h2>
    <ul>
        <li><a href="#">HTML5 Basics</a></li>
        <li><a href="#">CSS3 Features</a></li>
    </ul>
</aside>
```

### `<details>`
The `<details>` tag specifies additional details that the user can view or hide on demand. It can be used to create an interactive widget that the user can open and close.

#### Example
```html
<details>
    <summary>More Information</summary>
    <p>HTML5 is the latest version of the HTML standard.</p>
</details>
```

### `<figure>` and `<figcaption>`
The `<figure>` tag specifies self-contained content, like illustrations, diagrams, photos, code listings, etc. The `<figcaption>` tag defines a caption for a `<figure>` element.

#### Example
```html
<figure>
    <img src="example.jpg" alt="Example Image">
    <figcaption>Figure 1: An example image</figcaption>
</figure>
```

### `<footer>`
The `<footer>` tag defines a footer for a document or section. It often contains information about the author, copyright information, links to related documents, etc.

#### Example
```html
<footer>
    <p>&copy; 2024 Example Company. All rights reserved.</p>
</footer>
```

### `<header>`
The `<header>` tag specifies a header for a document or section. It often contains introductory content or navigational links.

#### Example
```html
<header>
    <h1>Welcome to My Website</h1>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
</header>
```

### `<main>`
The `<main>` tag specifies the main content of a document. The content inside the `<main>` element should be unique to the document and not repeated across documents (such as sidebars, navigation links, etc.).

#### Example
```html
<main>
    <h2>Main Content</h2>
    <p>This is the main content of the webpage.</p>
</main>
```

### `<mark>`
The `<mark>` tag highlights text. When used in a document, it indicates that the text is of special interest or relevance.

#### Example
```html
<p>The <mark>HTML5</mark> specification is a major update to HTML.</p>
```

### `<nav>`
The `<nav>` tag defines a set of navigation links. It is intended for major navigational blocks.

#### Example
```html
<nav>
    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
    </ul>
</nav>
```

### `<section>`
The `<section>` tag defines sections in a document, such as chapters, headers, footers, or any other sections of the document.

#### Example
```html
<section>
    <h2>Introduction</h2>
    <p>This is the introduction section of the document.</p>
</section>
```

### `<summary>`
The `<summary>` tag is used as a summary, heading, or caption for the `<details>` element.

#### Example
```html
<details>
    <summary>Read more</summary>
    <p>This is additional content that can be toggled on and off.</p>
</details>
```

### `<time>`
The `<time>` tag is used to represent a specific period in time. It can be used to encode dates and times in a machine-readable format.

#### Example
```html
<p>Posted on <time datetime="2024-07-13">July 13, 2024</time>.</p>
```

## Interview Questions and Answers

1. **What is the purpose of the `<article>` tag?**
   - **Answer:** The `<article>` tag specifies independent, self-contained content that can be reused or distributed independently.

2. **How does the `<aside>` tag differ from the `<article>` tag?**
   - **Answer:** The `<aside>` tag defines content that is indirectly related to the main content, often used for sidebars or related information, while the `<article>` tag is for standalone, self-contained content.

3. **How can you create an expandable/collapsible section in HTML?**
   - **Answer:** You can use the `<details>` and `<summary>` tags to create an expandable/collapsible section.
   - **Code Example:**
     ```html
     <details>
         <summary>More Information</summary>
         <p>HTML5 is the latest version of the HTML standard.</p>
     </details>
     ```

4. **What is the use of the `<figure>` and `<figcaption>` tags?**
   - **Answer:** The `<figure>` tag is used for self-contained content like images or diagrams, and `<figcaption>` provides a caption for the `<figure>`.
   - **Code Example:**
     ```html
     <figure>
         <img src="example.jpg" alt="Example Image">
         <figcaption>Figure 1: An example image</figcaption>
     </figure>
     ```

5. **How do you mark text as important or relevant in HTML?**
   - **Answer:** You can use the `<mark>` tag to highlight text that is of special interest or relevance.
   - **Code Example:**
     ```html
     <p>The <mark>HTML5</mark> specification is a major update to HTML.</p>
     ```

6. **Explain the difference between the `<header>` and `<footer>` tags.**
   - **Answer:** The `<header>` tag defines the introductory content or navigational links for a document or section, while the `<footer>` tag defines the footer for a document or section, often containing information like the author, copyright, or links.

7. **How can you represent a date or time in HTML?**
   - **Answer:** You can use the `<time>` tag to represent a specific period in time, and encode it in a machine-readable format.
   - **Code Example:**
     ```html
     <p>Posted on <time datetime="2024-07-13">July 13, 2024</time>.</p>
     ```

These notes, interview questions, and code examples provide a comprehensive overview of various HTML semantic elements.