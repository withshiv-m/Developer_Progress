#  Devloper Progress track
📄 index.html(15/05/2026)
# 🎨 CSS Selectors
This file shows how different **CSS selectors** work in HTML.
## 📌 Topics
* Class selector (`.red`)
* ID selector (`#green`)
* Element selector (`div`)
* Child selector (`div > p`)
* Descendant selector (`div p`)
* Universal selector (`*`)
* Pseudo selectors (`:hover`, `:active`, `:visited`, `:link`)
## 🚀 How to Run
Open the file in any browser and see how styles are applied.
---
✨ Basic example to understand CSS selectors.
--------------------------------------------------------------------------------------
📄 htmlstyle.html(30/05/2026)
This file demonstrates how to use the style attribute in HTML to apply inline styling.
#🎨 HTML Style Attribute
The **style attribute** in HTML is used to apply **inline CSS** directly to an element.
## 📌 Syntax
```html
<tag style="property: value;">
```
## 💡 Example
```html
<p style="color: blue; font-size: 18px;">
  This is a styled paragraph.
</p>
```
## ✅ Common Properties
* `color` → Text color
* `background-color` → Background color
* `font-size` → Size of text
* `text-align` → Alignment of text
## ⚡ Why Use It?
* Quick styling for small elements
* Useful for testing or simple designs
## ⚠️ Note
Avoid using inline styles in large projects. Use **external CSS** for better structure and maintainability.
---
⭐ Easy and fast way to style elements directly!
-----------------------------------------------------------------------------------------------------------
📄 br.html
date:30/05/2026
## 🏷️ Basic HTML Tags
| Tag     | Description                                 |
| ------- | ------------------------------------------- |
| `<p>`   | Defines a paragraph                         |
| `<hr>`  | Defines a thematic change (horizontal line) |
| `<br>`  | Inserts a single line break                 |
| `<pre>` | Defines preformatted text                   |

### 💡 Example
```html id="h2l9s8"
<p>This is a paragraph</p>
<hr>
<br>
<pre>
This text
is written
in preformatted style
</pre>
```
---
✨ These are commonly used basic HTML tags for structuring content.
---------------------------------------------------------------------------------------------------------
# 📄 formate.html(30/05/2026)
# 📝 HTML Text Formatting
This file demonstrates different **HTML text formatting tags**.

## 📌 Tags Used
* `<b>` → Bold text
* `<i>` → Italic text
* `<strong>` → Important text
* `<em>` → Emphasized text
* `<small>` → Smaller text
* `<sub>` → Subscript
* `<sup>` → Superscript
* `<mark>` → Highlighted text
* `<del>` → Deleted text
* `<ins>` → Inserted text
* 
## 🚀 How to Run
Open the file in a browser to see formatted text.
---
✨ Basic example to understand HTML text formatting.
-----------------------------------------------------------------------------------------
📄quotation.html(31/05/2026)
# 📘 HTML Quotation & Citation Elements
This project shows basic HTML quotation and citation tags.
## 🔹 Tags Included

* `<abbr>` – Abbreviation
* `<address>` – Contact info
* `<bdo>` – Text direction
* `<blockquote>` – Long quote
* `<cite>` – Title of work
* `<q>` – Short quote

## 🚀 Purpose
Learn semantic HTML and improve code readability.
-----------------------------------------------------------------------------------------
📄color.html(31/05/2025)
# 🎨 HTML Colors Example
This project demonstrates how to use different **color styles in HTML** using inline CSS.

## 🔹 Features
* Background colors using color names (Tomato, Orange, etc.)
* Text colors
* Border colors
* RGB, HEX, HSL color values
* Transparent colors using RGBA & HSLA

## 🚀 Concepts Covered
* `background-color`
* `color`
* `border`
* Different color formats:

  * RGB
  * HEX
  * HSL
  * RGBA
  * HSLA

## 📌 Purpose
Learn how to apply colors in HTML and understand different color formats.
---------------------------------------------------------------------------------------------------
📄font.html(31/05/2026)
# 🎨 HTML & CSS Styling Basics
This project covers the fundamentals of **HTML styling and CSS usage**.

## 🔹 Topics Covered
* Inline CSS using `style` attribute
* Internal CSS using `<style>`
* External CSS using `<link>`
* Use of `<head>` for styles

## 🎯 CSS Properties
* `color` → Text color
* `font-family` → Font style
* `font-size` → Text size
* `border` → Element border
* `padding` → Space inside border
* `margin` → Space outside border

## 🚀 Purpose
To understand how to style web pages using basic CSS techniques.
---------------------------------------------------------------------------------------------------
📄link.html(01/01/2026)
# 🔗 HTML Anchor Tags
This project shows how to use the **`<a>` tag** in HTML.

## 📌 Topics Covered

* Links using `href`
* `target` attribute (`_blank`, `_self`, etc.)
* Absolute vs Relative URLs
* Image as a link
* Email links (`mailto:`)

## 🌐 Examples

**Absolute URL**
```html
<a href="https://www.google.com">Google</a>
```

**Relative URL**
```html
<a href="shiv.jpg">Image</a>
```
**Image as Link**
```html
<a href="default.asp">
  <img src="smiley.gif" alt="img" width="42">
</a>
```
**Email Link**
```html
<a href="mailto:mugleshiv1531@gemail.com">Send Email</a>
```
## ⚠️ Note
Use only **one `<body>` tag** in HTML.
-----------------------------------------------------------------------------
Project:-
📄bookmark.html
# 🔖 HTML Bookmarks (Internal Links)
This project demonstrates how to create **bookmarks (internal links)** in HTML using the `<a>` tag and `id` attribute.

## 📌 Features
* Navigate within the same page
* Jump to specific sections (Chapter 4, 10, 20)
* Internal CSS styling
* External CSS using `color.css`

## 🔗 Example
```html
<a href="#C4">Go to Chapter 4</a>

<h2 id="C4">Chapter 4</h2>
```

## ⚙️ How It Works
* `href="#C4"` → links to section
* `id="C4"` → target section

## 🎯 Use Case
Helpful for long pages like:

* Documentation
* Notes
* Tutorials
--------------------------------------------------------------------------------------------------------------------------
📄img.html(1/06/2026)

✨ Features
🖼️ Display images using <img>
🗺️ Create interactive image maps
🎯 Click different parts of image for different actions
💡 Beginner-friendly HTML concepts

Here are the most common image file types, which are supported in all browsers (Chrome, Edge, Firefox, Safari, Opera):

Abbreviation	File Format	               File Extension
APNG	Animated Portable Network Graphics	.apng
GIF	     Graphics Interchange Format	     .gif
ICO	      Microsoft Icon	                 .ico, .cur
JPEG	Joint Photographic Expert Group image .jpg, .jpeg, .jfif, .pjpeg, .pjp
PNG	        Portable Network Graphics	      .png
SVG	     Scalable Vector Graphics	          .svg 

HTML Image Tags
Tag	       Description
<img>	     Defines an image
<map>	     Defines an image map
<area>	   Defines a clickable area inside an image map
<picture>	 Defines a container for multiple image resources

🎯 Clickable Areas
Area	Shape	Action
💻 Laptop	Rectangle	Opens link
📓 Notebook	Rectangle	Opens link
🖱️ Mouse	Circle	Opens link
