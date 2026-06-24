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

# 🖼️ HTML Image Tags Guide
This repository contains a simple guide to understanding **HTML image-related tags** and how they are used in web development.

---

## 📌 Overview
HTML provides several tags to display images and create interactive image areas. Below are the most commonly used image tags:

---

## 🏷️ HTML Image Tags

| Tag         | Description                                      |
| ----------- | ------------------------------------------------ |
| `<img>`     | Defines an image                                 |
| `<map>`     | Defines an image map                             |
| `<area>`    | Defines a clickable area inside an image map     |
| `<picture>` | Defines a container for multiple image resources |

---

## 🖼️ 1. `<img>` Tag
The `<img>` tag is used to display images on a webpage.

### Example:

```html
<img src="image.jpg" alt="Sample Image" width="300">
```

---

## 🗺️ 2. `<map>` Tag
The `<map>` tag is used to create an image map (clickable areas on an image).

---

## 🔲 3. `<area>` Tag
The `<area>` tag defines clickable regions inside an image.

### Example:

```html
<img src="image.jpg" usemap="#imagemap">

<map name="imagemap">
  <area shape="rect" coords="34,44,270,350" href="link.html" alt="Clickable Area">
</map>
```

---

## 🖼️ 4. `<picture>` Tag
The `<picture>` tag allows you to use multiple images for different screen sizes.

### Example:

```html
<picture>
  <source media="(max-width: 600px)" srcset="small.jpg">
  <source media="(max-width: 1200px)" srcset="medium.jpg">
  <img src="large.jpg" alt="Responsive Image">
</picture>
```
---

## 🚀 Features of This Repo
* Beginner-friendly explanation
* Simple examples
* Useful for practice and revision

---

## 📚 Conclusion
Understanding HTML image tags helps you:

* Display images effectively
* Create interactive UI
* Build responsive websites

---
⭐ If you found this helpful, consider giving this repo a star!
-----------------------------------------------------------------------------------------------------
📄favicon.html(02/06/2026)
# 🌐 HTML Favicon Guide

This repository explains how to add a **favicon (website icon)** to your HTML webpage.

---

## 📌 What is a Favicon?

A **favicon** is a small icon that appears:

* In the browser tab
* In bookmarks
* In browser history

It helps in **branding and easy identification** of your website.

---

## 🛠️ How to Add Favicon in HTML

Use the `<link>` tag inside the `<head>` section:

### ✅ Basic Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>Favicon Example</title>
    <link rel="icon" href="favicon.png" type="image/png">
</head>
<body>
    <h1>Hello World</h1>
</body>
</html>
```

---

## 📁 Folder Structure

Make sure your file structure is correct:

```
project/
 ├── index.html
 └── favicon.png
```

Or if using folder:

```
project/
 ├── index.html
 └── images/
      └── favicon.png
```

Then use:

```html
<link rel="icon" href="images/favicon.png" type="image/png">
```

---

## 🧾 Supported Formats

| Format | Type Value                   |
| ------ | ---------------------------- |
| `.ico` | image/x-icon                 |
| `.png` | image/png                    |
| `.jpg` | image/jpeg (not recommended) |

---

## ⚠️ Common Mistakes

* ❌ Wrong file path
* ❌ Incorrect `type` value
* ❌ Using `.jpg` (not reliable)
* ❌ Browser cache not cleared

---

## 💡 Tips
* Use **.png or .ico** format
* Keep size **16x16 or 32x32 pixels**
* Clear cache using **Ctrl + Shift + R**
* Test image path directly in browser

---

## 🚀 Conclusion
Adding a favicon improves:

* User experience
* Website branding
* Professional look

---
⭐ If you found this helpful, don’t forget to star this repository!
----------------------------------------------------------------------------------------------------
📄button.html(03/0/2026)
# 🔘 HTML Button
Simple example of using buttons in HTML.

## 🧱 Basic Button
```html
<button>Click Me</button>
```

## 🎨 Styled Button
```html
<button style="background:blue; color:white; padding:10px; border:none; border-radius:5px;">
  Click Me
</button>
```

## ⚙️ Types
```html
<button type="button">Button</button>
<button type="submit">Submit</button>
<button type="reset">Reset</button>
```

## 🚀 Features
* Easy to use
* Customizable with CSS
* Supports actions with JavaScript

--------------------------------------------------------------------------------------------------------------
📄first.css(04/06/2026)
## What is CSS?
* CSS is the language we use to style a Web page.

* CSS stands for Cascading Style Sheets
* CSS describes how HTML elements are to be displayed on screen, paper, or in other media
* CSS saves a lot of work. It can control the layout of multiple web pages all at once
* External stylesheets are stored in CSS files
---------------------------------------------------------------------------------------------------------------
#📄background.html(05/06/2026)
#📄background.css
# 🎨 CSS Background Properties Guide
This repository contains a simple and clear explanation of **CSS Background Properties** with examples.

---

## 📌 What are Background Properties?
CSS background properties are used to define the background effects of an element such as **color, image, position, size, and more**.

---

## 🧠 List of Background Properties

| Property                | Description                                                     |
| ----------------------- | --------------------------------------------------------------- |
| `background`            | Shorthand property to set all background properties in one line |
| `background-attachment` | Defines if background scrolls or stays fixed                    |
| `background-clip`       | Specifies the painting area of the background                   |
| `background-color`      | Sets the background color                                       |
| `background-image`      | Sets an image as background                                     |
| `background-origin`     | Defines where the background image is positioned                |
| `background-position`   | Sets the starting position of background image                  |
| `background-repeat`     | Defines how background image repeats                            |
| `background-size`       | Sets the size of the background image                           |

---

## 🔥 Example
```css
body {
  background-color: lightblue;
  background-image: url("bg.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  background-attachment: fixed;
}
```

---

## ⚡ Shorthand Example
```css
body {
  background: lightblue url("bg.jpg") no-repeat center/cover fixed;
}
```

---

## 💡 Key Points
* `background` saves time by combining all properties
* `background-size: cover` makes image fit full screen
* `background-attachment: fixed` creates parallax effect
* `background-repeat: no-repeat` prevents repeating

---

## 🎯 Use Cases
* Landing pages
* Portfolio websites
* Hero sections
* Parallax scrolling effects

---

## 🚀 Conclusion
CSS background properties help you create visually appealing designs with simple code.

---
⭐ If you found this helpful, give this repo a star!
-----------------------------------------------------------------------------------------------------------
📄border.html(06/06/2026)
# 🎨 CSS Border Properties Guide
This repository provides a complete overview of all CSS border properties with simple explanations. It is useful for beginners who want to understand how borders work in CSS.

---

## 📌 What are CSS Borders?

CSS borders are used to define the outline of an element. You can control the **width, style, color, and shape** of borders.

---

## 📋 All CSS Border Properties

| Property              | Description                                              |
| --------------------- | -------------------------------------------------------- |
| `border`              | Sets all the border properties in one declaration        |
| `border-bottom`       | Sets all the bottom border properties in one declaration |
| `border-bottom-color` | Sets the color of the bottom border                      |
| `border-bottom-style` | Sets the style of the bottom border                      |
| `border-bottom-width` | Sets the width of the bottom border                      |
| `border-color`        | Sets the color of the four borders                       |
| `border-left`         | Sets all the left border properties in one declaration   |
| `border-left-color`   | Sets the color of the left border                        |
| `border-left-style`   | Sets the style of the left border                        |
| `border-left-width`   | Sets the width of the left border                        |
| `border-radius`       | Sets rounded corners for borders                         |
| `border-right`        | Sets all the right border properties in one declaration  |
| `border-right-color`  | Sets the color of the right border                       |
| `border-right-style`  | Sets the style of the right border                       |
| `border-right-width`  | Sets the width of the right border                       |
| `border-style`        | Sets the style of the four borders                       |
| `border-top`          | Sets all the top border properties in one declaration    |
| `border-top-color`    | Sets the color of the top border                         |
| `border-top-style`    | Sets the style of the top border                         |
| `border-top-width`    | Sets the width of the top border                         |
| `border-width`        | Sets the width of the four borders                       |

---

## 💡 Example

```css
div {
  border: 2px solid black;
  border-radius: 10px;
}
```

---

## 🎯 Key Concepts
* Use `border` shorthand to write clean code
* Use `border-radius` for rounded corners
* Customize each side using `border-top`, `border-left`, etc.

---

## 🚀 Conclusion
Understanding CSS border properties helps you design visually appealing layouts and improve UI design.

---

## 👨‍💻 Author
**Shivprasad**
Frontend Developer (HTML, CSS, JavaScript)
---------------------------------------------------------------------------------------------------------------
📄margin.html(07/06/2026)
# 📦 CSS Margin Properties

This repository contains a simple explanation and examples of **CSS Margin Properties**, which are used to create space **outside** elements.

---

## 📖 What is Margin?

Margin is the space **outside the border** of an element. It helps in creating spacing between elements on a webpage.

---

## 🧩 CSS Margin Properties

| Property        | Description                                       |
| --------------- | ------------------------------------------------- |
| `margin`        | Shorthand property to set all margins in one line |
| `margin-top`    | Sets space above the element                      |
| `margin-right`  | Sets space to the right of the element            |
| `margin-bottom` | Sets space below the element                      |
| `margin-left`   | Sets space to the left of the element             |

---

## ✨ Syntax

```css
selector {
  margin: top right bottom left;
}
```

---

## 🧪 Example

```css
div {
  margin: 10px 20px 15px 5px;
}
```

👉 This means:

* Top → 10px
* Right → 20px
* Bottom → 15px
* Left → 5px

---

## 🔁 Shorthand Variations

```css
margin: 10px;                /* All sides */
margin: 10px 20px;          /* Top-Bottom | Left-Right */
margin: 10px 20px 30px;     /* Top | Left-Right | Bottom */
margin: 10px 20px 30px 40px;/* Top | Right | Bottom | Left */
```

---

## 📌 Important Notes

* Margin does **not affect element size**, only spacing
* Can accept values like:

  * `px`, `%`, `em`, `auto`
* `margin: auto` is used to **center elements horizontally**

---

## 🎯 Example: Centering a Box

```css
.box {
  width: 200px;
  margin: 0 auto;
}
```

---

## 🚀 Use Cases

* Creating space between sections
* Aligning elements
* Centering layouts
* Improving UI spacing

---

## 📁 Project Structure

```
📦 css-margin-properties
 ┣ 📄 README.md
 ┗ 📄 margin.html
```

---

## 🧠 Conclusion

CSS margins are essential for layout and spacing. Mastering them helps you build clean and well-structured web designs.

---
⭐ If you found this helpful, consider giving this repo a star!
--------------------------------------------------------------------------------------------------------------------------------
Text.css (09/06/2026)
# 🎨 CSS Text & Alignment Practice
This repository contains basic examples of **CSS properties** related to text styling, alignment, and decoration. It is useful for beginners learning CSS fundamentals.

---

## 📌 Topics Covered

### 1. Background & Text Color

```css
body {
    background-color: lightgray;
    color: blue;
}
```

* `background-color` → sets background color of the page
* `color` → sets text color

---

### 2. Text Alignment

```css
h1 {
    text-align: center;
}
```

#### Values:

* `left` → text aligned left
* `right` → text aligned right
* `center` → text centered
* `justify` → equal spacing

---

### 3. Vertical Alignment

```css
img.h1 {
    vertical-align: text-bottom;
}
```

Used to align elements vertically relative to surrounding content.

#### Values:

* `top` → align to top
* `middle` → center vertically
* `bottom` → align to bottom
* `text-top` / `text-bottom` → align with text

---

### 4. Text Decoration

```css
h1 {
  text-decoration-line: overline;
  text-decoration-line: line-through;
}
```

#### Types:

* `underline` → line below text
* `overline` → line above text
* `line-through` → line through text
* `none` → no decoration

---

## ⚠️ Note

If multiple `text-decoration-line` are used, the last one will override the previous one.

---

## 🚀 Purpose

This project is created to:

* Practice basic CSS properties
* Understand text styling
* Learn alignment techniques

---

## 📂 How to Use

1. Clone the repository
2. Open the HTML file in your browser
3. Modify CSS and experiment

---

## 👨‍💻 Author

Shivprasad

---

## ⭐ Support

If you found this helpful, give it a ⭐ on GitHub!
-------------------------------------------------------------------------------------
font.css(11/06/2026)
# 🎨 CSS Text Styling
## 📌 Overview

CSS text styling is used to control the appearance of text on a webpage. It helps improve readability, design, and user experience by applying different fonts, sizes, spacing, and alignment.

---

## 🔤 Font Properties

### 1. font-family

Defines the typeface of the text.

```css
font-family: 'Poppins', sans-serif;
```

---

### 2. font-size

Controls the size of the text.

```css
font-size: 16px;
```

---

### 3. font-weight

Sets the thickness of the text.

```css
font-weight: 400; /* normal */
font-weight: 600; /* bold */
```

---

### 4. font-style

Applies style like italic.

```css
font-style: italic;
```

---

## ✨ Text Properties

### 5. color

Sets the text color.

```css
color: #333;
```

---

### 6. text-align

Aligns text horizontally.

```css
text-align: center;
text-align: left;
text-align: right;
```

---

### 7. text-decoration

Adds or removes decoration.

```css
text-decoration: none;
text-decoration: underline;
```

---

### 8. text-transform

Controls capitalization.

```css
text-transform: uppercase;
text-transform: lowercase;
text-transform: capitalize;
```

---

### 9. letter-spacing

Controls space between characters.

```css
letter-spacing: 1px;
```

---

### 10. line-height

Controls spacing between lines.

```css
line-height: 1.6;
```

---

## 💡 Conclusion

CSS text styling plays an important role in creating visually appealing and readable web pages. By using proper font and text properties, developers can enhance the overall user interface and user experience.

---------------------------------------------------------------------------------------------------
icon.html(12/06/2026)
# 🎨 Icons Demo Project

## 📌 About

This project demonstrates how to use different icon libraries in a web page, including **Font Awesome** and **Google Material Icons**. It is a beginner-friendly project to understand how icons work in HTML using CDN links.

---

## 🚀 Features

* Use of Font Awesome icons
* Use of Google Material Icons
* Custom styling (size & color)
* Simple and clean HTML structure

---

## 🛠️ Technologies Used

* HTML5
* CSS (inline styling)
* Font Awesome CDN
* Google Fonts (Material Icons)

---

## 🔧 How It Works

### 1. Font Awesome Icons

Icons are added using class names:

```html
<i class="fa-solid fa-heart"></i>
<i class="fa-solid fa-car"></i>
```

---

### 2. Styling Icons

You can change size and color:

```html
<i class="fa-solid fa-cloud" style="font-size:40px; color:red;"></i>
```

---

### 3. Material Icons

Icons are used like text:

```html
<i class="material-icons">cloud</i>
<i class="material-icons">favorite</i>
```

---

## 📂 Project Structure

```bash
project-folder/
│── index.html
```

---

## ▶️ How to Run

1. Download or clone the repository
2. Open `index.html` in your browser
3. You will see all icons displayed

---

## 💡 Learning Outcome

* Learned how to use icon libraries
* Understood CDN integration
* Practiced basic HTML structure

---

## ⚠️ Important Notes

* Internet connection is required (CDN links)
* Make sure correct icon class names are used

---

## 📬 Contact

Feel free to connect with me for feedback or collaboration.

---

⭐ If you like this project, don't forget to star the repository!
---------------------------------------------------------------------------------------------
link.css(14/06/2026)
# 🎨 CSS Link & Button Styling Project

## 📌 Description

This project demonstrates how to style links and buttons using CSS pseudo-classes like `:hover`, `:active`, `:link`, and `:visited`.

It is a beginner-friendly project to understand how user interactions affect link appearance.

---

## 🚀 Features

* Change link color on hover
* Change link color when clicked (active state)
* Custom styling for visited links
* Styled buttons using anchor (`<a>`) tag
* Font change on hover for specific class

---

## 🧠 Concepts Covered

* CSS Pseudo-classes:

  * `:hover`
  * `:active`
  * `:link`
  * `:visited`
* Styling anchor tags as buttons
* Text decoration and font styling

---

## 💻 Code Example

```css
a:hover {
    color: red;
    text-decoration: dotted;
}

a:active {
    color: rgb(0, 255, 21);
}

a.four:link {
    color: red;
}

a.four:visited {
    color: blue;
}

a.four:hover {
    font-family: monospace;
}

/* Button Styling */
a:link, a:visited {
    background-color: #f44336;
    color: white;
    padding: 14px 25px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
}
```

---

## 📷 Output

* Links change color when hovered or clicked
* Button-style links with background color
* Different styles for visited links

---

## 🎯 Purpose
This project helps beginners understand:

* How CSS interacts with user actions
* How to create interactive UI elements
* Basics of front-end styling

---

## 🛠️ How to Use
1. Clone the repository
2. Open the HTML file in browser
3. Hover and click links to see effects

---

## 🙌 Author
**Shivprasad**

---

## ⭐ Support
If you like this project, give it a ⭐ on GitHub!
--------------------------------------------------------------------------------------------------------------------------------------
html.html(22/06/2026)
# 📌 Display vs Visibility Demo (HTML, CSS, JavaScript)

## 📖 Overview

This project demonstrates the difference between two important CSS properties:

* `display`
* `visibility`

It also includes simple JavaScript examples to dynamically show, hide, and reset elements on a webpage.

---

## 🚀 Features

* Toggle a hidden panel using `display: none` and `display: block`
* Understand how `visibility: hidden` works
* Interactive buttons to:

  * Remove elements from layout
  * Hide elements without removing space
  * Reset elements to original state

---

## 🧠 Key Concepts

### 🔹 `display: none`

* Completely removes the element from the page
* Element does **not take any space**

### 🔹 `visibility: hidden`

* Element becomes invisible
* Still **occupies space in layout**

---

## 📂 Project Structure

* HTML for structure
* CSS for styling and layout
* JavaScript for interaction

---

## ⚙️ How It Works

### 1. Toggle Panel

* A paragraph (`Click to show panel`) triggers a function
* JavaScript changes:

  * `display: none` → `display: block`

### 2. Remove Element

* Button sets:

  * `display: none`
* Element disappears completely

### 3. Hide Element

* Button sets:

  * `visibility: hidden`
* Element becomes invisible but space remains

### 4. Reset

* Restores:

  * `display: block`
  * `visibility: visible`

---

## 🖥️ Usage

1. Open the HTML file in your browser
2. Click buttons to see behavior
3. Observe layout changes carefully

---

## 🎯 Learning Outcome

After this project, you will understand:

* Difference between `display` and `visibility`
* DOM manipulation using JavaScript
* Basic UI interaction handling

---

## 📸 Example Use Cases

* Show/Hide menus
* Toggle modals or panels
* Control UI elements dynamically

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)

---

## 📌 Conclusion

This is a beginner-friendly project to clearly understand how elements behave in a webpage when using `display` and `visibility`.

---

## ⭐ Author

Shivprasad
(Frontend & Web Development Learner 🚀)
---
-----------------------------------------------------------------------------------------------------------------------------------------
position.html(23/06/2026)
# CSS Positioning Demo

This project demonstrates the different types of CSS `position` properties using simple HTML and CSS examples. It is designed for beginners who want to understand how elements are positioned on a webpage.

---

## 📌 Features

* Demonstrates 5 types of CSS positioning:

  * `static`
  * `relative`
  * `fixed`
  * `absolute`
  * `sticky`
* Simple and beginner-friendly code
* Scrollable page to test `sticky` behavior

---

## 📂 Project Structure

```
folder/
│── position.html
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/css-position-demo.git
```

### 2. Open the project

* Navigate to the project folder
* Open `index.html` in your browser

---

## 📖 Explanation of Positions

### 1. Static

* Default position
* Elements follow normal page flow

### 2. Relative

* Positioned relative to itself
* Can move using `top`, `left`, `right`, `bottom`

### 3. Fixed

* Stays fixed on screen even when scrolling
* Positioned relative to viewport

### 4. Absolute

* Positioned relative to nearest positioned ancestor
* Removed from normal flow

### 5. Sticky

* Acts like relative until scroll threshold
* Then sticks to a fixed position

---

## 🧪 How to Test

* Open the page in a browser
* Scroll down to see the **sticky element**
* Notice how:

  * Fixed element stays in place
  * Absolute element positions relative to page
  * Relative element shifts from its original position

---

## 🎯 Purpose

This project is useful for:

* Beginners learning CSS
* Practicing layout concepts
* Understanding positioning behavior visually

---

## 📸 Preview

Open the HTML file in your browser to see live behavior.

---

## 🛠️ Technologies Used

* HTML5
* CSS3

---

## 🤝 Contributing

Feel free to fork this repository and improve the examples.

---

## 📄 License

This project is open-source and free to use.

---

## 👨‍💻 Author

Shivprasad

---

⭐ If you found this helpful, don't forget to star the repo!
----------------------------------------------------------------------------------------------------------------------------------------
z-index.html(24/06/2026)
# 🎯 CSS Z-Index & Positioning Demo
This project demonstrates how **CSS positioning** and **z-index** work together to control the stacking order of elements on a webpage.

---

## 📌 Overview

In this example, we use different CSS positioning properties like:

* `relative`
* `absolute`
* `sticky`

Along with `z-index` to control which element appears **on top of others**.

---

## 🧱 Project Structure

* **Container** → Parent element with `position: relative`
* **Black Box** → Base element (`z-index: 1`)
* **Green Box** → Overlaps black box (`z-index: 2`)
* **Gray Box** → Topmost element (`z-index: 3`)

---

## 🚀 Key Concepts

### 🔹 Positioning

* `relative` → Positioned relative to itself
* `absolute` → Positioned relative to nearest positioned parent
* `sticky` → Switches between relative and fixed based on scroll

### 🔹 Z-Index

* Controls **stack order**
* Higher value → appears on top
* Works only on positioned elements

---

## 🖼️ Behavior

* Gray box appears above all elements (`z-index: 3`)
* Green box appears above black box (`z-index: 2`)
* Black box stays at the bottom (`z-index: 1`)

---

## 💡 Example Output

When you run this code:

* Elements overlap each other
* The stacking order is clearly visible

---

## 🛠️ How to Run

1. Copy the code into an `.html` file
2. Open it in any browser
3. Observe how elements overlap based on `z-index`

---

## 📚 Learning Purpose

This project is useful for beginners learning:

* CSS positioning
* Layout design
* Layer management in UI

---

## 🤝 Contributing

Feel free to fork this repository and experiment with different `z-index` values and positioning types.

---

## ⭐ Support

If you found this helpful, give it a ⭐ on GitHub!

---
