# html-for-beginner
# HTML Documentation for Beginner Web Developers

Welcome to the world of web development! HTML (Hypertext Markup Language) is the foundation of every web page. It defines the structure and content of a webpage. This comprehensive documentation will guide you through HTML's basics and provide you with detailed examples to make your learning journey smooth and enjoyable.

## Table of Contents

1. [Introduction to HTML](#introduction-to-html)
   1. [What is HTML?](#what-is-html)
   2. [Basic Structure of an HTML Document](#basic-structure-of-an-html-document)
   3. [HTML Elements and Tags](#html-elements-and-tags)

2. [Text and Headings](#text-and-headings)
   1. [Paragraphs `<p>`](#paragraphs-p)
   2. [Headings `<h1>` to `<h6>`](#headings-h1-to-h6)
   3. [Line Breaks `<br>`](#line-breaks-br)
   4. [Horizontal Rules `<hr>`](#horizontal-rules-hr)

3. [Links and URLs](#links-and-urls)
   1. [Anchor Tags `<a>`](#anchor-tags-a)
   2. [URL Structure](#url-structure)
   3. [Linking to Internal Pages](#linking-to-internal-pages)
   4. [Linking to External Pages](#linking-to-external-pages)
   5. [Linking to Email Addresses](#linking-to-email-addresses)

4. [Images](#images)
   1. [Adding Images `<img>`](#adding-images-img)
   2. [Image Attributes (Width, Height, Alt)](#image-attributes-width-height-alt)

5. [Lists](#lists)
   1. [Unordered Lists `<ul>`](#unordered-lists-ul)
   2. [Ordered Lists `<ol>`](#ordered-lists-ol)
   3. [Nested Lists](#nested-lists)

6. [Tables](#tables)
   1. [Creating Tables `<table>`](#creating-tables-table)
   2. [Table Rows `<tr>`](#table-rows-tr)
   3. [Table Headers `<th>`](#table-headers-th)
   4. [Table Data `<td>`](#table-data-td)
   5. [Spanning Rows and Columns](#spanning-rows-and-columns)

7. [Forms](#forms)
   1. [Form Structure `<form>`](#form-structure-form)
   2. [Text Input `<input type="text">`](#text-input-input-type"text")
   3. [Password Input `<input type="password">`](#password-input-input-typepassword)
   4. [Radio Buttons `<input type="radio">`](#radio-buttons-input-typeradio)
   5. [Checkboxes `<input type="checkbox">`](#checkboxes-input-typecheckbox)
   6. [Dropdown Menus `<select>`](#dropdown-menus-select)
   7. [Textareas `<textarea>`](#textareas-textarea)
   8. [Submit Buttons `<input type="submit">`](#submit-buttons-input-typesubmit)

8. [Divisions and Spans](#divisions-and-spans)
   1. [Divisions `<div>`](#divisions-div)
   2. [Spans `<span>`](#spans-span)

9. [Semantic Elements](#semantic-elements)
   1. [Headers `<header>`](#headers-header)
   2. [Navigation `<nav>`](#navigation-nav)
   3. [Main Content `<main>`](#main-content-main)
   4. [Articles `<article>`](#articles-article)
   5. [Sections `<section>`](#sections-section)
   6. [Asides `<aside>`](#asides-aside)
   7. [Footers `<footer>`](#footers-footer)

10. [Comments](#comments)
    1. [Adding Comments `<!-- -->`](#adding-comments-)

11. [Doctype and Meta Tags](#doctype-and-meta-tags)
    1. [Document Type Declaration](#document-type-declaration)
    2. [Character Encoding `<meta charset="UTF-8">`](#character-encoding-meta-charsetutf-8)
    3. [Viewport `<meta name="viewport">`](#viewport-meta-nameviewport)

12. [HTML Entities](#html-entities)
    1. [Special Characters](#special-characters)
    2. [Non-Breaking Space `&nbsp;`](#non-breaking-space-nbsp)

13. [HTML Validation](#html-validation)
    1. [W3C Markup Validation Service](#w3c-markup-validation-service)

## 1. Introduction to HTML

### What is HTML?

HTML stands for Hypertext Markup Language. It is the standard markup language used to create and design web pages. HTML uses various elements and tags to structure the content and define its layout.

### Basic Structure of an HTML Document

```html
<!DOCTYPE html>
<html>
<head>
    <title>Title of the Page</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```
## 2. Text and Headings

[Paragraphs `<p>`](#paragraphs-p)
Paragraphs are used to group text together.

```html
<p>This is the first paragraph.</p>
<p>This is the second paragraph.</p>
```
In this example, `<p>` is the opening tag, and `</p>` is the closing tag. The content between the opening and closing tags is the content of the paragraph. <br>
<br>
### Headings `<h1>` to `<h6>`
```html
<h1> Main Heading </h1>
<h2> Subheading </h2>
<h3> Sub-subheading </h3>
<h4> this h4 </h4>
<h5> this is h5 tag </h5>
<h6> this h6 tag </h6>
```
### Line Breaks `<br>` <br>
Headings define the hierarchy of the text on the page.
```html
<p>This is the first line.<br>This is the second line.</p>

```
### Horizontal Rules `<hr>`
Horizontal rules create a visual break between content.
```html
<p>This is some content.</p>
<hr>
<p>This is more content.</p>

```
## 3. Links and URLs
### Anchor Tags `<a>`
Anchor tags are used to create hyperlinks that allow users to navigate between web pages.
```html
<a href="https://www.example.com">Visit Example Website</a>

```
### URL Structure
URLs (Uniform Resource Locators) specify the web address of a resource.
```html
https://www.example.com/index.html
|       |           |        |
protocol  domain     path     file
```
### Linking to External Pages
Linking to external websites using absolute URLs.
```html
<a href="https://www.google.com">Google</a>
```

