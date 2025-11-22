# 🌐 HTML Complete Notes --- Beginner to Advanced

A **comprehensive guide** to HTML with detailed explanations, syntax,
examples, diagrams, and interview questions.

------------------------------------------------------------------------

## 📘 Table of Contents

1.  [Introduction to HTML](#introduction-to-html)
2.  [Basic Structure of an HTML
    Document](#basic-structure-of-an-html-document)
3.  [Text & Formatting Tags](#text--formatting-tags)
4.  [Lists](#lists)
5.  [Links & Navigation](#links--navigation)
6.  [Images, Audio & Video](#media-tags)
7.  [Tables](#tables)
8.  [Forms](#forms)
9.  [Semantic HTML](#semantic-html)
10. [HTML Metadata](#html-metadata)
11. [Script & Style](#script--style)
12. [Interview Questions](#interview-questions)

------------------------------------------------------------------------

# 📌 Introduction to HTML

**HTML (HyperText Markup Language)** is the standard language used to
create web pages.\
It tells the browser how to structure and display content.

HTML consists of: - **Elements** - **Tags** - **Attributes** -
**Content**

------------------------------------------------------------------------

# 🏗 Basic Structure of an HTML Document

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document Title</title>
</head>
<body>
    <h1>Hello World!</h1>
</body>
</html>
```

------------------------------------------------------------------------

# ✍ Text & Formatting Tags

## ➤ Headings

HTML provides 6 levels of headings:

``` html
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Section Title</h3>
```

## ➤ Paragraph

``` html
<p>This is a paragraph in HTML.</p>
```

## ➤ Bold / Italic / Underline

``` html
<b>Bold Text</b>
<i>Italic Text</i>
<u>Underlined Text</u>
```

## ➤ Span (inline)

``` html
<p>This is <span style="color: red;">highlighted</span> text.</p>
```

## ➤ Div (block-level)

``` html
<div style="background: #eee; padding: 10px;">
    This is a block container.
</div>
```

------------------------------------------------------------------------

# 📋 Lists

## ➤ Unordered List

``` html
<ul>
    <li>Item One</li>
    <li>Item Two</li>
</ul>
```

## ➤ Ordered List

``` html
<ol>
    <li>First</li>
    <li>Second</li>
</ol>
```

------------------------------------------------------------------------

# 🎬 Media Tags

## ➤ Image Tag

``` html
<img src="photo.jpg" alt="Sample Image" width="200">
```

## ➤ Audio Tag

``` html
<audio src="song.mp3" controls></audio>
```

## ➤ Video Tag

``` html
<video src="video.mp4" width="300" controls autoplay muted loop></video>
```

------------------------------------------------------------------------

# 📊 Tables

``` html
<table border="1">
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Divyansh</td>
        <td>21</td>
    </tr>
</table>
```

------------------------------------------------------------------------

# 📝 Forms

## ➤ Input

``` html
<input type="text" placeholder="Enter name">
```

## ➤ Textarea

``` html
<textarea rows="4" cols="30"></textarea>
```

## ➤ Select Dropdown

``` html
<select>
    <option>India</option>
    <option>USA</option>
</select>
```

## ➤ Full Form

``` html
<form>
    <label>Name:</label>
    <input type="text">

    <label>Message:</label>
    <textarea></textarea>

    <button type="submit">Submit</button>
</form>
```

------------------------------------------------------------------------

# 🔖 Semantic HTML

  Tag           Meaning
  ------------- ---------------------
  `<header>`    Page Header
  `<footer>`    Page Footer
  `<nav>`       Navigation Links
  `<section>`   Section of content
  `<article>`   Independent article
  `<aside>`     Sidebar

Example:

``` html
<header>My Website</header>
<nav>Home | About | Contact</nav>
<section>
    <article>This is a blog post.</article>
</section>
<aside>Sidebar content</aside>
<footer>©2025 Divyansh</footer>
```

------------------------------------------------------------------------

# 🧠 HTML Metadata

``` html
<head>
    <meta charset="UTF-8">
    <meta name="description" content="HTML Notes">
    <title>HTML Notes</title>
</head>
```

------------------------------------------------------------------------

# 🧩 Script & Style

## ➤ Script Tag

``` html
<script>
    console.log("Hello from JS");
</script>
```

## ➤ Style Tag

``` html
<style>
    h1 { color: blue; }
</style>
```

------------------------------------------------------------------------

# 🎯 Interview Questions

### ⭐ Basic Level

1.  What is HTML?\
2.  What is the difference between `<div>` and `<span>`?\
3.  What are block-level and inline elements?\
4.  Explain semantic HTML.

### ⭐ Medium Level

5.  What is the purpose of DOCTYPE?\
6.  Explain the difference between `<id>` and `<class>`.\
7.  What are self-closing tags?\
8.  What is the use of `<meta>` tags?

### ⭐ Advanced Level

9.  Why is semantic HTML important for SEO & accessibility?\
10. Difference between HTML5 and previous versions?\
11. What is DOM?\
12. How does browser rendering work?

------------------------------------------------------------------------

# 🚀 Final Notes

This repository contains **every HTML tag example** organized neatly
into folders.\
Use it as your personal **HTML handbook**!
